# Integration Test Scenarios

## Scenario 1: Timer and Momentum Tracker

**Goal**
Verify that completing a timer session correctly updates the momentum tracker.

**Steps**
1. Start a timer for a task
2. Allow timer to complete
3. Log completion

**Expected Result**
Momentum tracker reflects completed task session.

---

## Scenario 2: Navigation State

**Goal**
Verify task state persists when navigating between screens.

**Steps**
1. Create a new task
2. Navigate to a different screen
3. Return to task list

**Expected Result**
The task remains visible in the list.

