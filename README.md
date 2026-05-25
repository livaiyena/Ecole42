<div align="center">
  <h1>Ecole 42 Project Portfolio</h1>
  <p><em>A comprehensive collection of my curriculum projects at Ecole 42.</em></p>
</div>

---

## Overview

Welcome to my Ecole 42 project showcase. This repository serves as a centralized hub containing the major projects I have completed during my studies. Each project is integrated as a Git submodule, ensuring its individual commit history, project structure, and documentation remain intact and accessible.

This setup provides a seamless navigation experience through my academic progression and technical growth.

## Project Roster

The projects below are listed in chronological order of their completion:

| Project | Description | Primary Technology |
| :--- | :--- | :--- |
| **[libft](./libft/)** | Custom C standard library containing fundamental functions and data structures. | `C` |
| **[printf](./printf/)** | Implementation of the `printf` function, handling variadic arguments and formatting. | `C` |
| **[get_next_line](./get_next_line/)** | Memory-safe, leak-free function designed to read lines from a file descriptor. | `C` |
| **[push_swap](./push_swap/)** | Highly optimized algorithm project focusing on stack-based sorting operations. | `C` |
| **[Python-Modules](./Python-Modules/)** | Foundational modules and scripts introducing Python programming concepts. | `Python` |
| **[a-maze-ing](./a-maze-ing/)** | Interactive maze generator showcasing robust error management and rendering. | `Python` |

---

## Setup & Initialization

Due to the use of submodules, special flags are required to clone this repository completely.

### Initial Clone

To clone the repository and automatically fetch all nested project contents, use the `--recursive` flag:

```bash
git clone --recursive git@github.com:livaiyena/Ecole42.git
```

### Existing Clone

If the repository was cloned without the recursive flag, you can initialize and update the submodules by running:

```bash
git submodule update --init --recursive
```

---
<div align="center">
  <i>Developed and maintained by livaiyena</i>
</div>
