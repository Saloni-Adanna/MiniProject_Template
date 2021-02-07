# STEPin MiniProject_Template Sample

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/3b20c7c3ec7f4734b42cc0d04dcf3fb2)](https://app.codacy.com/manual/stepin654321/MiniProject_Template?utm_source=github.com&utm_medium=referral&utm_content=stepin654321/MiniProject_Template&utm_campaign=Badge_Grade_Dashboard)


|Build|Unit Test|cppcheck|Valgrind|Codacy|
|:--:|:--:|:--:|:--:|:--:|
|![C/C++ CI](https://github.com/stepin654321/MiniProject_Template/workflows/C/C++%20CI/badge.svg)|![Unit testing](https://github.com/stepin654321/MiniProject_Template/workflows/Unit%20testing/badge.svg)|![cppcheck-action](https://github.com/stepin654321/MiniProject_Template/workflows/cppcheck-action/badge.svg)|![Valgrind](https://github.com/stepin654321/MiniProject_Template/workflows/Valgrind/badge.svg)|[![Codacy Badge](https://app.codacy.com/project/badge/Grade/3ac7e2a959a24fa4b5d1b9c1c886ff75)](https://www.codacy.com/manual/stepin654321/MiniProject_Template?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=stepin654321/MiniProject_Template&amp;utm_campaign=Badge_Grade)|

## Integrated Tools to GitHub
*  [Codacy](https://www.codacy.com/)

## GitHub Actions
* Build using Make for CI
* Unit tests with Cunit
* Static code analysis using cppcheck
* Dynamic Code analysis using Valgrind


Instructions to setup gitinspector[linux]

Install Python 2 (It's a dependency)
sudo apt install python
Remove system package (Short story, it's messed up)
sudo apt -y remove gitinspector
Clone the repo from github to any directory and add it to path
git clone https://github.com/ejwa/gitinspector.git
cd gitinspector
echo "export PATH=$(pwd):"'$PATH' >> ~/.profile
source ~/.profile
Run gitinspector with "gitinspector.py" like so
gitinspector.py -wTHl --format=htmlembedded -f c,h,md,yml,* path/to/your/repo > result.html
You can open the result.html file in a web browser to see the results

