# Description

Skeleton Extas package.

# Usage

```bash
# composer create-project jeyroik/extas-skeleton <package directory name>
# cd <package directory name>
<package directory name># vendor/bin/build run
```

You should see dialog like this:

```bash
Please enter the name of the package: 
Please enter package owner name: 
```

After typing package name (without `extas`-prefix), and owner name you should see:

```bash
Starting building package "<package name>>" by "<owner name>"...

 - composer.json updated
 - extas.json updated
 - README.md updated
 - CODECOV.md updated
 - CODECLIMATE.md updated
 - tests/<package name>/<Package name>Test.php updated

Package building finished.

Please, do now:
 - See codecov instructions in the CODECOV.md.
 - See code climate instructions in the CODECLIMATE.md.
 - Paste code-climate link into README.md.
```
