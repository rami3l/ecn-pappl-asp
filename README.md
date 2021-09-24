# ecn-pappl-asp

## Table of Contents

- [ecn-pappl-asp](#ecn-pappl-asp)
  - [Table of Contents](#table-of-contents)
  - [Use the AnsProlog environment in Docker](#use-the-ansprolog-environment-in-docker)
  - [On the motivation of ASP](#on-the-motivation-of-asp)
  - [First steps with AnsProlog](#first-steps-with-ansprolog)

## Use the AnsProlog environment in Docker

1. Install `docker` and `docker-compose`.
2. Run `docker compose up`.
3. Find in the log a link that looks like `http://127.0.0.1:8888/?token=*` and access it with your browser.
4. Open a new `Python` notebook, and type your script under the `%%clingo -V0 0` cell magic. For example:

   ```prolog
   %%clingo -V0 0
   {a; b}.
   ```

## On the motivation of ASP

- [Wiki on ASP](https://en.wikipedia.org/wiki/Answer_set_programming)

## First steps with AnsProlog

- [AnsProlog Notes](https://www.cs.cmu.edu/~cmartens/asp-notes.pdf)
