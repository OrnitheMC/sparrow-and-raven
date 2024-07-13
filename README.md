# Sparrow

Java signature mappings for classes, fields, and methods.

# Raven

Java exceptions clause mappings for methods.

## Contributing

1. Fork and clone this repository.
2. Change the Minecraft version in `build.gradle` (line 44) to the version you wish to work on.
3. Run `./gradlew setUpSource`.
4. Import this project into your Java IDE. It will have the deobfuscated Minecraft source in the main sourceset.
5. Edit the source and add signatures.
  - This means adding generics to classes, fields, or methods, or adding throws clauses to method declarations.
  - Be careful not to change any class names, field names, or method names!
  - You may have to solve compile errors in order to save your work. This is because the decompilation process is imperfect.
6. Run `./gradlew save`. Your progress is now saved in the `/signatures/` and `/exceptions/` directories.
7. Commit and push your work.
8. Open a pull request with your changes.
