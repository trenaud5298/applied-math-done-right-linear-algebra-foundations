# Applied Math Done Right: Linear Algebra Foundations

This repository contains the source for *Applied Math Done Right: Linear Algebra Foundations*, an applied mathematics book focused on developing core linear algebra concepts while applying those concepts in a small C++ linear algebra library

The book is written with [Quarto](https://quarto.org/) and is currently planned to have HTML, PDF, and EPUB versions. The HTML version will feature solutions to all exercises in the book while the PDF and EPUB version will omit these for brevity.

## Project Goals

This project aims to create a strong foundational book that will build the readers Linear Algebra foundations and coding skills in preparation for applying these skills towards a real world problem. This book aims to be the first in a series of books that will build upon each other. The next book in this series plans to build upon both the linear algebra skills and C++ library developed throughout this book to explore the field of Ray Tracing through the applications of Linear Algebra.

## Audience

This book is written for readers who already know the basics of C++. This book does not aim to teach the basics of programming in C++ and assumes the reader is already familiar with basic C++ syntax and class design. Readers are expected to understand concepts such as classes, member functions, constructors, operator overloading, exceptions, and separation of header and source files. The library built throughout this book will use CMake as the build system, although a detailed understanding is not needed or expected of the user. The reader will only be expected to be able to either build the project using CMake, or if they are comfortable through any other build system so long as they are able to properly configure it for this project.

## Repository Structure

```text
chapters/       Book chapter source files
appendices/     Appendix source files
assets/         Images, diagrams, and other book assets
code/           Starter and completed C++ library projects
references.bib  Bibliography data
_quarto.yml     Quarto book configuration
```

## How to Read This Book

Each chapter of this book aims to first introduce mathematical concepts first, and then develops the structure for corresponding C++ design. The goal of this structure is for readers to gain core Linear Algebra skills and to understand what and how to implement these concepts through programming exercises.

Most chapters follow this pattern

1. Introduce the focused mathematical concept
2. Demonstrate small drafts of C++ design related to the concept
3. Provide small math focused checkpoints after each section
4. Provide larger math and programming focused exercises at the end of the chapter


## Exercises and Solutions

Exercises include both traditional mathematical problems and coding exercises focused on implementing the C++ designs that were discussed throughout the chapter. This will usually take the form of implementing one or more classes, but may also take on other forms depending on the context.

In the HTML version of this book, solutions are included in collapsable sections for each exercise. In the PDF version, solutions are omitted for brevity.

## Source Code

The project includes starter code and completed reference code. The starter code is intended for readers who want to work through the implementation exercises, while the completed code is intended for readers to be able to check their work and run tests to compare their output with a reference.

As mentioned previously, this book will not focus on teaching C++ fundamentals or how to build the project. Basic build instructions can be found on the GitHub repository for this book, which is also where you can find all materials related to this book.

## Mathematical Style

This book is not intended to be proof-heavy. Some definitions and justifications are included in this book, but the emphasis is on applying these concepts through programming instead. Some exercises in the book will also ask the reader to use the code they built to test various theorems or conjectures to see if the results line up with expectations.

## License

The book content and source code are free to use for noncommercial purposes. See [LICENSE.md](LICENSE.md) and [LICENSE-CODE.md](LICENSE-CODE.md) for the specific terms that apply to the written material and to the code respective.