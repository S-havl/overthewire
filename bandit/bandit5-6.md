ls
cd inhere
find . -type f -size 1033c ! -executable -exec file {} + | grep -i 'text'
cd maybehere07
ls -la
cat .file2
