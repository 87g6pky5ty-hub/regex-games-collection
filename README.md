# Awesome Regex Games & Fun Things 🎮

A comprehensive collection of regex games, interactive challenges, learning tools, and resources to make mastering regular expressions fun and engaging!

---

## Table of Contents

- [🎮 Regex Games](#-regex-games)
- [🛠️ Interactive Learning Tools](#️-interactive-learning-tools)
- [📚 Curated Collections & Resources](#-curated-collections--resources)
- [🔤 Regex Flavors & Implementations](#-regex-flavors--implementations)
- [🌐 Online Testers & Visualizers](#-online-testers--visualizers)

---

## 🎮 Regex Games

### Direct Playable Games

| Game | Repository | Description | Tech Stack |
|------|------------|-------------|-----------|
| **Regex Challenge Game** | [merjohnpagente/regex-challenge-game](https://github.com/merjohnpagente/regex-challenge-game) | Web-based game where you match regex patterns by typing matching strings. Features random challenges, timer, points, hints, and score tracking. | HTML, CSS, Vanilla JS |
| **RegEx Game (Terminal)** | [EDJAE/RegEx_game](https://github.com/EDJAE/RegEx_game) | Terminal-style regex training game. Read a pattern, type a matching string, race against the clock. Multiple difficulty levels, hints, and scoring. | Terminal/CLI |
| **RegEx Quest** | [Deadsecnote1/RegEx-Quest](https://github.com/Deadsecnote1/RegEx-Quest) | Browser-based game with interactive challenges and puzzles of varying difficulty. Track your progress as you solve regex problems. | Web-based |
| **RegExtris** | [SA3-Games/RegExtris](https://github.com/SA3-Games/RegExtris) | Tetris-inspired game where you use regex patterns to clear lines. Features learn mode for guidance, blending classical gameplay with regex puzzles. | Web-based |

---

## 🛠️ Interactive Learning Tools

### Educational Platforms

| Tool | Repository | Description | Features |
|------|------------|-------------|----------|
| **RegexLab** | [ThatSINEWAVE/RegexLab](https://github.com/ThatSINEWAVE/RegexLab) | Interactive web application to test, build, and learn regex with visual tools and playground | Pattern builder, tester, comprehensive cheat sheet, visual tools |
| **RegexLearn.com** | [aykutkardas/regexlearn.com](https://github.com/aykutkardas/regexlearn.com) | Step-by-step interactive regex lessons from beginner to advanced with live playground and feedback | 21+ languages, multiple learning tracks, live regex playground, interactive lessons |

---

## 📚 Curated Collections & Resources

### Awesome Regex Lists

| Collection | Repository | Description |
|------------|------------|-------------|
| **Awesome Regex (Aloisdg)** | [aloisdg/awesome-regex](https://github.com/aloisdg/awesome-regex) | Curated collection of regex libraries, tools, frameworks, visual testers, generators, and exercises |
| **Awesome Regex (slevithan)** | [slevithan/awesome-regex](https://github.com/slevithan/awesome-regex) | Comprehensive regex references, recommendations, interactive testers, and learning resources |
| **RegEx Awesome List** | [newbie2soc/RegEx_Awesome_List](https://github.com/newbie2soc/RegEx_Awesome_List) | Well-maintained fork with organized navigation and regularly updated content |

---

## 🔤 Regex Flavors & Implementations

Regular expressions come in many different flavors, each with variations in syntax, features, and performance characteristics. Here's a comprehensive breakdown:

### PCRE (Perl Compatible Regular Expressions)
- **Language/Tool**: Perl, PHP, NGINX, Apache
- **Characteristics**: Feature-rich, supports lookahead/lookbehind, atomic groups, named captures
- **Use Case**: Server-side validation, text processing
- **Tools**: [PCRE Library](https://www.pcre.org/)
- **Test Online**: Regex101 (PCRE mode)

### ECMAScript / JavaScript (ES6+)
- **Language/Tool**: JavaScript, Node.js, Browsers
- **Characteristics**: Limited features in older versions, ES2018+ added lookbehind and named groups
- **Use Case**: Client-side validation, DOM manipulation
- **Modern Features**: Lookahead, lookbehind, named captures, Unicode support
- **Documentation**: [MDN Web Docs - RegExp](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
- **Test Online**: Regex101 (ECMAScript mode)

### Python (re & regex modules)
- **Language/Tool**: Python 2.x and 3.x
- **Standard Library**: `re` module (PCRE-like)
- **Extended Module**: `regex` module (PyPI - more features)
- **Characteristics**: Clean syntax, supports grouping, lookahead/lookbehind in `regex` module
- **Use Case**: Text processing, data extraction, scripting
- **Test Online**: Regex101 (Python flavor)

### Java
- **Language/Tool**: Java, Android
- **Characteristics**: Java Pattern class, supports most PCRE features, Unicode support
- **Use Case**: Server applications, Android development
- **Features**: Named groups, lookahead/lookbehind, Unicode blocks
- **Documentation**: [Java Pattern Class](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html)
- **Test Online**: Regex101 (Java 8 mode)

### .NET / C#
- **Language/Tool**: C#, ASP.NET, PowerShell, VB.NET
- **Characteristics**: Powerful, supports named groups, balancing groups, atomic groups
- **Use Case**: Windows development, web applications
- **Features**: Named captures, balancing groups, zero-width assertions
- **Documentation**: [Microsoft .NET Regex](https://docs.microsoft.com/en-us/dotnet/standard/base-types/regular-expressions)
- **Test Online**: Regex101 (.NET mode)

### POSIX (Basic & Extended)
- **Language/Tool**: C, UNIX utilities (grep, sed, awk), shell scripting
- **Basic (BRE)**: Minimal features, requires escaping metacharacters
- **Extended (ERE)**: More intuitive, standard in modern tools
- **Characteristics**: Simple, portable, limited features
- **Use Case**: System administration, text processing, scripting
- **Tools**: grep, sed, awk, tr

### Go (golang/regexp)
- **Language/Tool**: Go, Kubernetes, Docker, Terraform
- **Type**: RE2-like (deterministic, no backtracking)
- **Characteristics**: Fast, predictable performance, subset of PCRE
- **Limitations**: No lookahead/lookbehind, no backreferences to different groups
- **Use Case**: High-performance systems, cloud infrastructure tools
- **Documentation**: [Go regexp Package](https://golang.org/pkg/regexp/)

### Rust (regex crate)
- **Language/Tool**: Rust, embedded systems
- **Type**: Thompson NFA engine (no backtracking)
- **Characteristics**: Fast, memory-safe, subset of PCRE
- **Features**: Named groups, lookahead/lookbehind in newer versions
- **Use Case**: Systems programming, performance-critical applications
- **Crates**: [regex](https://crates.io/crates/regex), [regex-syntax](https://crates.io/crates/regex-syntax)

### Ruby (Regexp)
- **Language/Tool**: Ruby on Rails, Chef, Puppet
- **Type**: Similar to PCRE
- **Characteristics**: Full-featured, readable syntax
- **Features**: Named captures, lookahead/lookbehind, Unicode support
- **Use Case**: Web development, automation, DevOps
- **Test Online**: Rubular (Ruby-specific regex tester)

### PHP (PCRE & mb_ereg)
- **Language/Tool**: PHP, Laravel, WordPress
- **PCRE Functions**: `preg_*` functions (PCRE library)
- **mbstring Functions**: `mb_ereg*` (ONIGURUMA regex library)
- **Characteristics**: Full PCRE support, Unicode handling
- **Use Case**: Web development, content management systems
- **Documentation**: [PHP PCRE](https://www.php.net/manual/en/book.pcre.php)

### RE2 (Google's Regex Engine)
- **Language/Tool**: C++, Python (pyRE2), Go
- **Type**: Deterministic finite automaton
- **Characteristics**: Fast, predictable, no backtracking, no lookahead/lookbehind
- **Use Case**: Large-scale text processing, security-sensitive applications
- **Repository**: [google/re2](https://github.com/google/re2)

### Oniguruma (Onig)
- **Language/Tool**: Ruby (default), PHP (mbstring), Jpcre2
- **Characteristics**: Feature-rich, supports many regex flavors
- **Use Case**: Text processing with Unicode support
- **Repository**: [K-Takata/Oniguruma](https://github.com/K-Takata/Oniguruma)

### TCL (TclRE)
- **Language/Tool**: TCL, Expect
- **Characteristics**: POSIX ERE-like with some extensions
- **Use Case**: Systems administration, automation

### MySQL/MariaDB
- **Type**: POSIX ERE
- **Functions**: `REGEXP`, `RLIKE`
- **Characteristics**: Limited regex features
- **Use Case**: Database queries, pattern matching in SQL

### SQLite
- **Type**: Limited regex (custom function)
- **Characteristics**: No built-in regex, requires extension
- **Use Case**: Mobile apps, local database queries

### Lua
- **Type**: Custom pattern matching (simpler than regex)
- **Characteristics**: Limited features, non-standard syntax
- **Use Case**: Game development, embedded scripting
- **Documentation**: [Lua Pattern Matching](https://www.lua.org/pil/20.2.html)

### VimScript (Vim/Neovim)
- **Type**: Similar to POSIX with extensions
- **Characteristics**: Editor-specific syntax
- **Use Case**: Text editing, Vim automation

### Perl 6 / Raku
- **Language/Tool**: Raku (formerly Perl 6)
- **Characteristics**: Redesigned regex engine, more powerful syntax
- **Features**: Named captures, subrule calls, better readability
- **Use Case**: Text processing, parsing

### PCRE2 (Modern PCRE)
- **Language/Tool**: Modern version of PCRE library
- **Characteristics**: Improved performance, additional features
- **Use Case**: Performance-critical applications requiring PCRE compatibility
- **Repository**: [PCRE2 Library](https://www.pcre.org/)

---

## 🌐 Online Testers & Visualizers

### Interactive Regex Testers

| Tool | URL | Supported Flavors | Features |
|------|-----|------------------|----------|
| **Regex101** | https://regex101.com/ | PCRE, JavaScript, Python, Java, .NET, Golang, Rust | Real-time matching, explanation, cheat sheet, save patterns |
| **RegExr** | https://regexr.com/ | JavaScript | Visual highlighting, expression explorer, detailed reference |
| **Debuggex** | https://debuggex.com/ | JavaScript, Python, PCRE | Regex as flowchart/diagram visualization |
| **Rubular** | https://rubular.com/ | Ruby | Ruby-specific regex tester with live preview |
| **Regex Pal** | https://www.regexpal.com/ | JavaScript | Simple online tester with history |

### Regex Visualizers

| Tool | URL | Description |
|------|-----|-------------|
| **Regulex** | https://jex.im/regulex/ | Visualizes regex as railroad diagrams |
| **Regexper** | https://regexper.com/ | SVG railroad diagram generator |
| **Regviz** | https://regviz.org/ | State machine visualization |

---

## 🎓 Quick Reference

### By Use Case

**Beginners:** Start with [RegexLearn.com](https://github.com/aykutkardas/regexlearn.com) or [RegextrisGame](https://github.com/SA3-Games/RegExtris)

**Practitioners:** Use [Regex101](https://regex101.com/) or [RegExr](https://regexr.com/) for testing

**Challenge Seekers:** Try [Regex Challenge Game](https://github.com/merjohnpagente/regex-challenge-game) or [RegEx Quest](https://github.com/Deadsecnote1/RegEx-Quest)

**Visual Learners:** Explore [Debuggex](https://debuggex.com/) or [Regulex](https://jex.im/regulex/)

### By Regex Flavor

- **JavaScript Projects:** Use [Regex101 ECMAScript](https://regex101.com/), [RegExr](https://regexr.com/)
- **Python Projects:** Use [Regex101 Python](https://regex101.com/), [Debuggex](https://debuggex.com/)
- **Ruby Projects:** Use [Rubular](https://rubular.com/)
- **PHP/PCRE:** Use [Regex101 PCRE](https://regex101.com/)
- **Java/C#:** Use [Regex101](https://regex101.com/) with appropriate flavor selector

---

## 📖 Resources

- **Official Regex Guides:**
  - [MDN RegExp Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
  - [Regular Expressions Info](https://www.regular-expressions.info/)
  
- **Learning Materials:**
  - [Regex One](https://regexone.com/) - Interactive tutorial
  - [PCRE Documentation](https://www.pcre.org/)
  - [Regex Cheat Sheets](https://www.regular-expressions.info/reference.html)

---

## 🤝 Contributing

Have a regex game or tool to add? Feel free to submit a PR or open an issue with suggestions!

---

## 📜 License

This collection is compiled from various open-source projects. Please refer to individual repositories for their specific licenses.

Happy regex learning! 🎉
