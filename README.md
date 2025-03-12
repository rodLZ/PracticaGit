"# Hello World"

En la clase de zucco vimos como usar github ya que no teniamos conocimiento de esta cosa:

Microsoft Windows [Versión 10.0.19045.5487]
(c) Microsoft Corporation. Todos los derechos reservados.

C:\Users\Alumnos>cd ..

C:\Users>cd ..

C:\>cd Users/Alumnos

C:\Users\Alumnos> cd/rod
El sistema no puede encontrar la ruta especificada.

C:\Users\Alumnos> cd rod

C:\Users\Alumnos\rod>git init
Initialized empty Git repository in C:/Users/Alumnos/rod/.git/

C:\Users\Alumnos\rod>git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

C:\Users\Alumnos\rod>git add .
warning: in the working copy of 'CMakeLists.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'cmake-build-debug/CMakeFiles/clion-environment.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'main.cpp', LF will be replaced by CRLF the next time Git touches it

C:\Users\Alumnos\rod>git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Alumnos@DESKTOP-0JGG92V.(none)')

C:\Users\Alumnos\rod>git config --local user.email "rodrigo.lima@uniat.edu.mx"

C:\Users\Alumnos\rod>git config --local user.name "rod567"

C:\Users\Alumnos\rod>git commit
Aborting commit due to empty commit message.

C:\Users\Alumnos\rod>git commit
Aborting commit due to empty commit message.

C:\Users\Alumnos\rod>git commit -m
error: switch `m' requires a value

C:\Users\Alumnos\rod>git commit -n
[master (root-commit) f32db45]  On branch master  Initial commit  Changes to be committed:      new file:   .idea/.gitignore    new file:   .idea/misc.xml      new file:   .idea/modules.xml   new file:   .idea/rod.iml       new file:   CMakeLists.txt      new file:   cmake-build-debug/.cmake/api/v1/query/cache-v2      new file:   cmake-build-debug/.cmake/api/v1/query/cmakeFiles-v1         new file:   cmake-build-debug/.cmake/api/v1/query/codemodel-v2  new file:   cmake-build-debug/.cmake/api/v1/query/toolchains-v1         new file:   cmake-build-debug/.cmake/api/v1/reply/cache-v2-ebef420ed153d762acd5.json    new file:   cmake-build-debug/.cmake/api/v1/reply/cmakeFiles-v1-1785d1ba540105ff8831.json       new file:   cmake-build-debug/.cmake/api/v1/reply/codemodel-v2-25994921f5dffec6092f.json        new file:   cmake-build-debug/.cmake/api/v1/reply/directory-.-Debug-d0094a50bb2071803777.json   new file:   cmake-build-debug/.cmake/api/v1/reply/index-2025-03-12T20-13-50-0484.json   new file:   cmake-build-debug/.cmake/api/v1/reply/target-rod-Debug-382bedfd4a18623edb33.json    new file:   cmake-build-debug/.cmake/api/v1/reply/toolchains-v1-561666ebc7bc8e05dce9.json       new file:   cmake-build-debug/CMakeCache.txt    new file:   cmake-build-debug/CMakeFiles/3.24.2/CMakeCCompiler.cmake    new file:   cmake-build-debug/CMakeFiles/3.24.2/CMakeCXXCompiler.cmake  new file:   cmake-build-debug/CMakeFiles/3.24.2/CMakeDetermineCompilerABI_C.bin         new file:   cmake-build-debug/CMakeFiles/3.24.2/CMakeDetermineCompilerABI_CXX.bin       new file:   cmake-build-debug/CMakeFiles/3.24.2/CMakeRCCompiler.cmake   new file:   cmake-build-debug/CMakeFiles/3.24.2/CMakeSystem.cmake       new file:   cmake-build-debug/CMakeFiles/3.24.2/CompilerIdC/CMakeCCompilerId.c  new file:   cmake-build-debug/CMakeFiles/3.24.2/CompilerIdC/a.exe       new file:   cmake-build-debug/CMakeFiles/3.24.2/CompilerIdCXX/CMakeCXXCompilerId.cpp    new file:   cmake-build-debug/CMakeFiles/3.24.2/CompilerIdCXX/a.exe     new file:   cmake-build-debug/CMakeFiles/CMakeOutput.log        new file:   cmake-build-debug/CMakeFiles/TargetDirectories.txt  new file:   cmake-build-debug/CMakeFiles/clion-environment.txt  new file:   cmake-build-debug/CMakeFiles/cmake.check_cache      new file:   cmake-build-debug/CMakeFiles/rules.ninja    new file:   cmake-build-debug/build.ninja       new file:   cmake-build-debug/cmake_install.cmake       new file:   main.cpp
 35 files changed, 5520 insertions(+)
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/rod.iml
 create mode 100644 CMakeLists.txt
 create mode 100644 cmake-build-debug/.cmake/api/v1/query/cache-v2
 create mode 100644 cmake-build-debug/.cmake/api/v1/query/cmakeFiles-v1
 create mode 100644 cmake-build-debug/.cmake/api/v1/query/codemodel-v2
 create mode 100644 cmake-build-debug/.cmake/api/v1/query/toolchains-v1
 create mode 100644 cmake-build-debug/.cmake/api/v1/reply/cache-v2-ebef420ed153d762acd5.json
 create mode 100644 cmake-build-debug/.cmake/api/v1/reply/cmakeFiles-v1-1785d1ba540105ff8831.json
 create mode 100644 cmake-build-debug/.cmake/api/v1/reply/codemodel-v2-25994921f5dffec6092f.json
 create mode 100644 cmake-build-debug/.cmake/api/v1/reply/directory-.-Debug-d0094a50bb2071803777.json
 create mode 100644 cmake-build-debug/.cmake/api/v1/reply/index-2025-03-12T20-13-50-0484.json
 create mode 100644 cmake-build-debug/.cmake/api/v1/reply/target-rod-Debug-382bedfd4a18623edb33.json
 create mode 100644 cmake-build-debug/.cmake/api/v1/reply/toolchains-v1-561666ebc7bc8e05dce9.json
 create mode 100644 cmake-build-debug/CMakeCache.txt
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CMakeCCompiler.cmake
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CMakeCXXCompiler.cmake
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CMakeDetermineCompilerABI_C.bin
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CMakeDetermineCompilerABI_CXX.bin
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CMakeRCCompiler.cmake
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CMakeSystem.cmake
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CompilerIdC/CMakeCCompilerId.c
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CompilerIdC/a.exe
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CompilerIdCXX/CMakeCXXCompilerId.cpp
 create mode 100644 cmake-build-debug/CMakeFiles/3.24.2/CompilerIdCXX/a.exe
 create mode 100644 cmake-build-debug/CMakeFiles/CMakeOutput.log
 create mode 100644 cmake-build-debug/CMakeFiles/TargetDirectories.txt
 create mode 100644 cmake-build-debug/CMakeFiles/clion-environment.txt
 create mode 100644 cmake-build-debug/CMakeFiles/cmake.check_cache
 create mode 100644 cmake-build-debug/CMakeFiles/rules.ninja
 create mode 100644 cmake-build-debug/build.ninja
 create mode 100644 cmake-build-debug/cmake_install.cmake
 create mode 100644 main.cpp

C:\Users\Alumnos\rod>git switch -c Feature1
Switched to a new branch 'Feature1'

C:\Users\Alumnos\rod>echo "# Hello World">>README.md

C:\Users\Alumnos\rod>git add .

C:\Users\Alumnos\rod>git commit
[Feature1 fa914c2]  On branch Feature1  Changes to be committed:        new file:   README.md
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\Alumnos\rod>git remode ad origin https://github.com/rodLZ/PracticaGit.git
git: 'remode' is not a git command. See 'git --help'.

The most similar command is
        remote

C:\Users\Alumnos\rod>git remode add origin https://github.com/rodLZ/PracticaGit.git
git: 'remode' is not a git command. See 'git --help'.

The most similar command is
        remote

C:\Users\Alumnos\rod>git remote add origin https://github.com/rodLZ/PracticaGit.git

C:\Users\Alumnos\rod>git push -u origin Feature1
info: please complete authentication in your browser...
Enumerating objects: 48, done.
Counting objects: 100% (48/48), done.
Delta compression using up to 8 threads
Compressing objects: 100% (44/44), done.
Writing objects: 100% (48/48), 53.76 KiB | 3.36 MiB/s, done.
Total 48 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), done.
remote:
remote: Create a pull request for 'Feature1' on GitHub by visiting:
remote:      https://github.com/rodLZ/PracticaGit/pull/new/Feature1
remote:
To https://github.com/rodLZ/PracticaGit.git
 * [new branch]      Feature1 -> Feature1
branch 'Feature1' set up to track 'origin/Feature1'.

C:\Users\Alumnos\rod>