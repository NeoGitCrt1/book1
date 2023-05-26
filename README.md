# Introduction

// install nvm
nvm install 12.18.1
nvm use 12.18.1
npm install gitbook-cli -g
gitbook -V
gitbook init


.
├── book.json  配置数据 (可选)
├── README.md  电子书的前言或简介 (必需)
├── SUMMARY.md  电子书目录 (可选)
├── GLOSSARY.md  词汇/注释术语列表 (可选)
├── chapter-1/
|   ├── README.md
|   └── something.md
└── chapter-2/
    ├── README.md
    └── something.md


gitbook build
gitbook serve    