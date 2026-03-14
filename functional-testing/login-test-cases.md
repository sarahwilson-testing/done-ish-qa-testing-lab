# Functional Test Cases

## Test Case: Create New Task

**Precondition**
User is on the main task screen.

**Steps**
1. Tap the "Add Task" button
2. Enter a task name
3. Save the task

**Expected Result**
The new task appears in the task list.

---

## Test Case: Start Micro-Commit Timer

**Precondition**
At least one task exists.

**Steps**
1. Select a task
2. Tap the "Start Timer" button

**Expected Result**
The timer begins counting down.

---

## Test Case: Complete Task

**Precondition**
Timer session has been completed.

**Steps**
1. Tap "Log Completion"

**Expected Result**
The task is marked complete and momentum score updates.

