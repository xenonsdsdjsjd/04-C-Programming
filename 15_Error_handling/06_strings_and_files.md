# Strings and Files


#### STRINGS
Many string functions update ERRNO.

Most string functions return useful return values.

Ensure char arrays are **nul-terminated** before passing to string functions.


#### FILES
Permission erros will create ERRNOs and return NULL.

The *FILE* data type utilizes pointers and should be treated as such.

Missing files coupled with certain *modes* will create ERRNOs and return NULL.
