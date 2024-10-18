# SLOC

Program to measure the SLOC of software projects.

## Help

sloc

    Usage: sloc DIRECTORIES...
    
    This program reads the "pkg/SLOC" file in the specified directories
    and measures the SLOC (Source Lines Of Code).
    
    The "pkg/SLOC" has the following format "LANGUAGE COMMAND...". For
    example:
    
      Go       sloc-go .
      HTML/JS  sloc-gen . -name *.html
    
    See also: find(1)

sloc-gen

    Usage: sloc-gen [-l][-s SED] FIND-COMMAND
    
    Measure source lines of code in a project.

sloc-go

    Usage: sloc-go [-l] [DIR] [FILES]
    
    Measure source lines of code of Go projects.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
