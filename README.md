Google Style Guides
===================

Every major open-source project has its own style guide: a set of conventions
(sometimes arbitrary) about how to write code for that project. It is much
easier to understand a large codebase when all the code in it is in a
consistent style.

“Style” covers a lot of ground, from “use camelCase for variable names” to
“never use global variables” to “never use exceptions.” This project
([google/styleguide](https://github.com/google/styleguide)) links to the
style guidelines we use for Google code. If you are modifying a project that
originated at Google, you may be pointed to this page to see the style guides
that apply to that project.

This project holds the [C++ Style Guide][cpp], [Swift Style Guide][swift], [Objective-C Style Guide][objc],
[Java Style Guide][java], [Python Style Guide][py], [R Style Guide][r],
[Shell Style Guide][sh], [HTML/CSS Style Guide][htmlcss],
[JavaScript Style Guide][js], [AngularJS Style Guide][angular],
[Common Lisp Style Guide][cl], and [Vimscript Style Guide][vim]. This project
also contains [cpplint][cpplint], a tool to assist with style guide compliance,
and [google-c-style.el][emacs], an Emacs settings file for Google style.

If your project requires that you create a new XML document format, the [XML
Document Format Style Guide][xml] may be helpful. In addition to actual style
rules, it also contains advice on designing your own vs. adapting an existing
format, on XML instance document formatting, and on elements vs. attributes.

The style guides in this project are licensed under the CC-By 3.0 License,
which encourages you to share these documents.
See [https://creativecommons.org/licenses/by/3.0/][ccl] for more details.

The following Google style guides live outside of this project:
[Go Code Review Comments][go] and [Effective Dart][dart].


### 定制 Java Code Style

为了保留 IDE 部分常用的风格, 进行了部分定制。

#### IntelliJ-IDEA 定制

修改 `intellij-java-google-style.xml` 中的内容:

|项|原始取值|定制之后|定制时间|备注|
|:----|:----|:----|:----|:----|
|`INDENT_SIZE`| 2 | 4 |20200201|行缩进|
|`TAB_SIZE`| 2 | 4 |20200201|TAB 缩进|
|`CONTINUATION_INDENT_SIZE`| 2 or 4 | 8 |20200201|换行缩进|
|`RIGHT_MARGIN`| 100 | 120 |20200201|单行长度|
|`JD_PRESERVE_LINE_FEEDS`| 无 | true |20200201|保留代码注释中的手动换行|
|`KEEP_LINE_BREAKS`| 无 | true |20200201|保留Java代码中的手动换行|




<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

[cpp]: https://google.github.io/styleguide/cppguide.html
[swift]: https://google.github.io/swift/
[objc]: objcguide.md
[java]: https://google.github.io/styleguide/javaguide.html
[py]: https://google.github.io/styleguide/pyguide.html
[r]: https://google.github.io/styleguide/Rguide.html
[sh]: https://google.github.io/styleguide/shell.xml
[htmlcss]: https://google.github.io/styleguide/htmlcssguide.html
[js]: https://google.github.io/styleguide/jsguide.html
[angular]: https://google.github.io/styleguide/angularjs-google-style.html
[cl]: https://google.github.io/styleguide/lispguide.xml
[vim]: https://google.github.io/styleguide/vimscriptguide.xml
[cpplint]: https://github.com/google/styleguide/tree/gh-pages/cpplint
[emacs]: https://raw.githubusercontent.com/google/styleguide/gh-pages/google-c-style.el
[xml]: https://google.github.io/styleguide/xmlstyle.html
[go]: https://golang.org/wiki/CodeReviewComments
[dart]: https://www.dartlang.org/guides/language/effective-dart
[ccl]: https://creativecommons.org/licenses/by/3.0/
