If you are opening a new issue or submitting a pull request, **go for it!**
Don't be afraid that it's a dumb idea or a duplicate of another
issue or an unwanted change or whatever, especially if this is your first time
participating with us. We're glad to have you! :^)

## Code

For typo fixes and other small changes, you can use the GitHub web interface to
propose changes.

### Pull Requests.

Please use [a fork and pull request](https://help.github.com/articles/using-pull-requests/) to submit your work for code review. Please keep your pull requests as small as possible, and rebase your work onto the end of master before submitting it.

### Formatting

We use [Google's Java code formatting style](https://google.github.io/styleguide/javaguide.html). 

Before writing your code please use the following snippet to ensure that your IDE formats correctly. 

#### OS X IntelliJ IDEA 14 (Ultimate Edition)
```bash
curl --create-dirs -so ~/Library/Preferences/IntelliJIdea14/codestyles/intellij-java-google-style.xml https://raw.githubusercontent.com/google/styleguide/gh-pages/intellij-java-google-style.xml
```

#### OS X IntelliJ IDEA 14 (Community Edition)
```bash
curl --create-dirs -so ~/Library/Preferences/IdeaIC14/codestyles/intellij-java-google-style.xml https://raw.githubusercontent.com/google/styleguide/gh-pages/intellij-java-google-style.xml
```

#### IntelliJ IDEA 14  code style  scheme selection 
```
Preferences -> Code Style -> Java -> Scheme -> GoogleStyle
```

#### Eclipse 
- Download `https://github.com/google/styleguide/blob/gh-pages/eclipse-java-google-style.xml`. Import it into eclipse by going to *Window -> Preferences -> Java -> Code Style -> Formatter* and select *GoogleStyle*

## Testing

All changes **must** have tests to validate them.

A minimum of 80% coverage is required. Use `mvn clean test verify` to generate coverage reports (they appear in the `target/` folder).

No code will be merged until tests are passing
