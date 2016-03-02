---
layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff.png"
short-description: Blocitoff is a self-destructing to-do list application.

---
[![Blocitoff]({{ site.baseurl }}/img/blocitoff.png)](https://github.com/cobunny/Blocitoff)

## Explanation

Trying to use the simple UI design to maximize the focus on the functionality and easy accessibility.

## Problem

Need to archive the tasks that haven’t been completed and are expired from a pre-defined timer.
Having trouble seeing all the completed tasks and all the expired tasks. <br> 
What if the user wants to re-add the completed tasks and re-schedule the expired tasks?

## Solution

Create separate lists for all the COMPLETED TASKS, all the ACTIVE TASKS and all the EXPIRED TASKS.

On the ACTIVE TASK list, according to the user’s input, the tasks that are marked as completed will be instantly removed from the ACTIVE TASKS list and be placed onto the COMPLETED TASKS list, which is sorted by its priority value.  The completed tasks can be removed from the COMPLETED TASKS list and re-added to the ACTIVE TASKS list by simply clicking on it.

By using the pre-defined timer, calculate and remove the expired tasks from the ACTIVE TASKS list to the EXPIRED TASKS list.  The expired task can be rescheduled also by a simple click on it as well.

## Results

Solving the problem with the solutions above.

## Conclusion

Complete and manual deletion of any active task is optional.  The tasks can disappear from the ACTIVE TASKS list automatically if it is expired or just by the user marking it as a completed task. 