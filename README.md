See: [https://go.dev/doc/tutorial/fuzz](https://go.dev/doc/tutorial/fuzz)

*Trying out fuzzing in beta version of go 1.18* 

Tutorial: Getting started with fuzzing

Note: This is beta content.

This tutorial introduces the basics of fuzzing in Go. With fuzzing, random data is run against your test in an attempt to find vulnerabilities or crash-causing inputs. Some examples of vulnerabilities that can be found by fuzzing are SQL injection, buffer overflow, denial of service and cross-site scripting attacks.

In this tutorial, you’ll write a fuzz test for a simple function, run the go command, and debug and fix issues in the code.

For help with terminology throughout this tutorial, see the Go Fuzzing glossary.
