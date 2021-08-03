# Ghmattimysql Ready for use

```lua
local rows = exports.ghmattimysql:executeSync("SELECT * FROM example WHERE example = @example", {example = "example"})

exports.ghmattimysql:execute("SELECT * FROM example WHERE example = @example", {example = "example"}, function(rows)

end)
```