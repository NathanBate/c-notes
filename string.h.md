[back](README.md)

# string.h — C Standard Library Functions

This table comes from ChatGPT


| Category              | Function | Description |
|-----------------------|----------|-------------|
| **String Copying**    | `strcpy` | Copy a string (including null terminator). |
|                       | `strncpy` | Copy up to *n* characters. |
| **String Concatenation** | `strcat` | Append one string to another. |
|                       | `strncat` | Append up to *n* characters. |
| **String Comparison** | `strcmp` | Compare two strings. |
|                       | `strncmp` | Compare up to *n* characters. |
| **String Search**     | `strchr` | Find first occurrence of a character. |
|                       | `strrchr` | Find last occurrence of a character. |
|                       | `strstr` | Locate a substring. |
|                       | `strpbrk` | Find first occurrence of any accepted character. |
|                       | `strcspn` | Length of segment without rejected characters. |
|                       | `strspn` | Length of segment with only accepted characters. |
|                       | `strtok` | Split string into tokens (modifies input). |
| **String Length**     | `strlen` | Get length of string (excluding null terminator). |
| **Memory Operations** | `memcpy` | Copy memory block. |
|                       | `memmove` | Copy memory block (safe for overlap). |
|                       | `memset` | Fill memory with a byte value. |
|                       | `memcmp` | Compare memory blocks. |
|                       | `memchr` | Locate first occurrence of a byte. |

> **Note:** The above list follows the C17 standard (ISO/IEC 9899:2018).  
> Functions like `strdup`, `strndup`, `strtok_r`, and `strerror` are **POSIX/GNU extensions** and may not be available on all platforms.