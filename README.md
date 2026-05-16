# c.plus.plus.2026.course

Repository with small C++ programs used during the 2026 Linux C++ course.

## Included Programs

| File | Description |
|---|---|
| `suma.cpp` | Requests two numbers and prints the sum. |
| `time.cpp` | Displays the current execution time. |
| `systeminfo.cpp` | Shows basic Linux system information. |
| `pathvalidator.cpp` | Checks whether a path is a file, directory, symbolic link, or another type. |

## Compilation

```bash
g++ suma.cpp -o suma
g++ time.cpp -o time
g++ systeminfo.cpp -o systeminfo
g++ pathvalidator.cpp -o pathvalidator -std=c++17
