# ld64-static
Wrapper around ld64 to force static compilation by using a sandbox profile that prevents ld64 from seeing libfoo.dylib and only libfoo.a. Useful for linking against homebrew libraries statically.
