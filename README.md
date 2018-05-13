# TodoList

The application allows you to save and manage a list of your cases.

### Smart contract

- `add(date, text, completed)` - Adds a new task.
- `update(id, text, completed)` - Updates an existing task.
- `delete(id)` - Deletes the task.
- `get(limit, offset, taskType = 'any')` - Returns the specified number of task.
- `getByWallet(wallet)` - Returns all tasks of the user with the specified wallet.