# Bash Scripting Cheat Sheet

## Basic Script Structure
```bash
#!/bin/bash
# This is a comment
```

## Variables
```bash
name="Claude"              # No spaces around =
echo "Hello, $name"        # Variable expansion
echo 'Hello, $name'        # No expansion with single quotes
readonly CONSTANT="value"  # Constant variable
```

## String Tests
```bash
[ -z "$string" ]    # Is empty?
[ -n "$string" ]    # Is not empty?
[ "$a" = "$b" ]     # Equal?
[ "$a" != "$b" ]    # Not equal?
```

## File Tests
```bash
[ -f "$file" ]      # Is regular file?
[ -d "$dir" ]       # Is directory?
[ -x "$file" ]      # Is executable?
[ -r "$file" ]      # Is readable?
[ -w "$file" ]      # Is writable?
```

## Numeric Comparisons
```bash
[ "$a" -eq "$b" ]   # Equal
[ "$a" -ne "$b" ]   # Not equal
[ "$a" -gt "$b" ]   # Greater than
[ "$a" -lt "$b" ]   # Less than
[ "$a" -ge "$b" ]   # Greater or equal
[ "$a" -le "$b" ]   # Less or equal
```

## Control Structures
```bash
# If statement
if [ condition ]; then
    command
elif [ condition ]; then
    command
else
    command
fi

# For loop
for i in 1 2 3 4 5; do
    echo $i
done

# While loop
while [ condition ]; do
    command
done
```

## Input/Output
```bash
read name             # Read input
echo "Text"           # Print to stdout
echo "Error" >&2      # Print to stderr
```

## Functions
```bash
my_function() {
    echo "Parameter 1: $1"
    local local_var="I'm local"
    return 0
}
```

## Error Handling
```bash
set -e               # Exit on error
set -u               # Exit on undefined variable
set -o pipefail      # Exit on pipe failure
trap cleanup EXIT    # Cleanup on script exit
```

Would you like me to elaborate on any of these sections or see some practical examples?
