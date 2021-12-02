# starstruck license

derived from the **[code credit license](https://codecreditlicense.com)**

> show that you care

this repository contains development files for legal terms that software developers can use to require credit for their work.  you can find the legal terms built from these development files [on the github releases page](https://github.com/ey3tech/starstruck-license/releases) and at <https://codecreditlicense.com>.

using those legal terms, software developers can require the same kind of credit that contributors to other kinds of work---motion pictures, music, video games, books, and so on---[already receive](./conventions.md).  they can also help to establish a norm of appropriate credit in the software industry.

the license adds a credit requirement to the [blue oak model license](https://blueoakcouncil.org/license/1.0.0), a very permissive license like mit or bsd, but revised for maximum legal clarity and readability.

the license exception adds a credit requirement to any other license.  common open source software licenses like mit, bsd, apache, blue oak, and gpl do not effectively require credit.  but applying, say, the mit license _plus_ the credit requirement gives others all the rights they usually receive under the mit license, so long as they give credit.

## status

that text is a [flipped form](https://flippedform.com/) in everyday english.  if something doesn't make sense to you, that's the terms' fault, not yours.  please [open an issue on github](https://github.com/ey3tech/starstruck-license/issues/new) so we can fix it together.

## using the terms

the terms will are available to use in two ways:

1.  as a complete license that grants broad permission to use your software, but requires credit.

2.  as an add-on to an existing license, like mit, bsd, apache, or gpl.

those who want to use the complete license can copy it where they would usually copy mit, bsd, apache, gpl, or the like.

those who want to use the exception can append the exception's text to text of mit, bsd, apache, gpl, and so on.

## permission

each contributor licenses you to do everything with the legal text that would otherwise infringe that contributor's copyright in it.

if you make changes to the legal text, you must change or remove the title of the text.

***as far as the law allows, the legal text comes as is, without any warranty at all, and no contributor will be liable to anyone for any damages related to the text or its use, for any kind of legal claim.***

## building

to build official markdown copies, run `make`.  to build pdf copies, run `make pdf`.  you will need:

- `awk`
- `fmt`
- `grep`
- `make`
- pandoc
