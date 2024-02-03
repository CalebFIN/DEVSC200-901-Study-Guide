# __JSON__


JSON (JavaScript Object Notation) is a staple in web development, known for its simplicity and ability to make developers cry with a single misplaced comma. It's a format that's both easy to read (if you haven't been staring at it for 12 hours straight) and write.

**Author Note**: "Pretty Print is your friend"
  ```python
  import pprint
```

### Key Features
- **Lightweight**: Like your backpack after your laptop battery dies.
- **Human-readable**: Mostly by those who dream in code.
- **Language Independent**
- **Data Types**: Basically everything - supports strings, numbers, booleans, null, arrays, and objects.

#### Important Info
- **Objects**: Think of it as a sandwich. The bread (`{}`) holds together your ingredients (key:value pairs).

Key | : |  Value
---|---|---
 "developer" | : |  "John Doe"  

```json
{
  "developer": "John Doe",
  "coffeeConsumed": "2L",
  "codeStatus": "It's complicated"
}
```

- **Arrays**: A list of things you need to do but will probably procrastinate on.

```json
{
  "toDoList": [
    "Survive meeting without coffee",
    "Finish toDoList"
  ]
}
```

- **Strings**: Must be in double quotes, because JSON is fancy like that.

```json
{
  "favoriteQuote": "It works on my machine."
}
```

- **Numbers**: How many bugs you fixed today (or introduced).

```json
{
  "bugsFixed": 0,
  "newBugsIntroduced": "Error, Environment not found"
}
```

- **Booleans and Null**: The truth about whether your code is running yet, and the contents of your completed tasks list.

```json
{
  "isCodeWorking": false,
  "completedTasks": null
}
```
