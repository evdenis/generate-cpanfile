# generate-cpanfile
Grep perl files in directory. Generates cpanfile according to use directives. Excludes core modules.

```
   $ ./gen_cpanfile .
   requires 'File::Find::Rule';
   requires 'File::Slurp';
```
