FRSH
====

FRSH (pronounced: fresh) is a shell that attempts to be _friendly_ to the
commoners; a FReindly SHell.

Examples
--------

```shell
frsh create file somefile.txt
# Equivalent to `touch somefile.txt`

frsh append text to file somefile.txt "Hello, World!"
# `echo "Hello, World!" >> somefile.txt`
```

Roadmap
-------

This is planned to be developed in Golang, possibly using a package like Cobra.
It's also planned to have an interactive shell, which can accept the same
commands as shown in the `Examples` section, above.
