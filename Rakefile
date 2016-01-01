desc 'create a new draft post'
task :post do
    title = ENV['title']
  slug = "#{Time.now.to_s.split(' ')[0]}-#{title.downcase.gsub(/[^\w]+/, '-')}"

  file = File.join(
    File.dirname(__FILE__),
    '_posts',
      slug + '.md'
  )

  File.open(file, "w") do |f|
    f << <<-EOS.gsub(/^    /, '')
    ---
    layout: post
    title: #{title}
    ---

    EOS
  end

  system ("#{ENV['EDITOR']} #{file}")
end
