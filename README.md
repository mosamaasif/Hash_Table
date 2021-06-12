[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Hash Table</h3>

  <p align="center">
  Implementation of the Hash Table Data Structure
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <ul>
        <li><a href="#how-to-run">How to Run</a></li>
      </ul>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This is an implementation of the <a href="https://en.wikipedia.org/wiki/Hash_table"><i>Hash Table</i></a> Data Structure in C++ that I made as part of an assignment in my Data Structures Course at the University. Hash Table is a special Data Strcture that uses any object as a key into an array of other objects (key, value pair). The key is generated by hashing the objects and generating some integer value. Different hashing techniques are used. This uses very simple bitwise operations to manipulate the values, and caters for certain types such as uint64, string/const char*, char etc. If a key hashes to same index, it uses linked list to store them at that index. Also it increases size of Table by finding next largest prime, since that can prevent issues caused by even/odd bias, or using comp address which fills up half the table etc.


### Built With

* [C++](https://en.wikipedia.org/wiki/C%2B%2B)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* C++ - Google for your OS.
* [git](https://git-scm.com)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/saeenyoda/Hash_Table.git
   ```


<!-- USAGE EXAMPLES -->
## Usage

### How to Run
1. Open up command line or terminal and navigate to the cloned repo's directory
   ```sh
   cd "PATH-TO-DIRECTORY"
   ```
2. Run the main.cpp file (Using terminal on mac)
   ```sh
   clang++ -std=c++14 -stdlib=libc++ -I "PATH-TO-includes-FOLDER" "PATH-TO-main.cpp" "PATH-TO-file.cpp" -o out/release/main 
   ```

***NOTE:***  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`The instructions given above are for mac and that too using the terminal. For other OS and IDEs refer to the relevant docs.`
 

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/saeenyoda/Inverted_Indexing?label=license&style=for-the-badge
[license-url]: https://github.com/saeenyoda/Inverted_Indexing/blob/master/LICENSE
