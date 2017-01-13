# picoCTF SQL Injection Problem

This is the definition for an SQL injection problem for the picoCTF
capture-the-flag competition platform.

## Running locally

To run the problem, it needs to be included as part of an existing instance
of picoCTF.

Using the [example VM][1], create a folder inside the `/vagrant` folder
named `problems`.

Inside the `problems` folder, checkout this repository. Then follow the usual
picoCTF instructions to load the problems and run the web server.

Note that this repository only contains the problem definition. The [actual
problem][2] runs in a separate Docker container.

[1]: https://github.com/picoCTF/picoCTF-Platform-2
[2]: https://github.com/rubenarakelyan/ctf-sql-injection-vm

## Licence

[MIT License](LICENSE)
