````markdown
# 0x03. Shell, Variables, Expansions

This repository contains scripts for the **ALX System Engineering & DevOps** project 0x03, which focuses on **Shell, Init files, Variables, Expansions, Arithmetic, and Aliases**. Each script is written in **Bash**, executable, and exactly **two lines long** (unless otherwise noted for advanced tasks).

## Scripts

### 0-alias
- **Description:** Creates an alias `ls` that actually runs `rm *`.
- **Usage:**
  ```bash
  source ./0-alias
  \ls
````

* **Notes:** Temporary alias in current shell session.

### 1-hello_you

* **Description:** Prints `hello <current_user>`.
* **Usage:**

  ```bash
  ./1-hello_you
  ```
* **Output Example:**

  ```
  hello julien
  ```

### 2-path

* **Description:** Adds `/action` at the end of `$PATH`.
* **Usage:**

  ```bash
  source ./2-path
  echo $PATH
  ```
* **Output Example:**
  `/usr/local/bin:/usr/bin:/bin:/action`

### 3-paths

* **Description:** Counts the number of directories in `$PATH`.
* **Usage:**

  ```bash
  . ./3-paths
  ```
* **Output Example:** `11`

### 4-global_variables

* **Description:** Lists all **global (environment) variables**.
* **Usage:**

  ```bash
  source ./4-global_variables
  ```

### 5-local_variables

* **Description:** Lists **all local variables, environment variables, and functions**.
* **Usage:**

  ```bash
  . ./5-local_variables
  ```

### 6-create_local_variable

* **Description:** Creates a new **local variable** `BEST=School`.
* **Usage:**

  ```bash
  ./6-create_local_variable
  ```

### 7-create_global_variable

* **Description:** Creates a new **global variable** `BEST=School`.
* **Usage:**

  ```bash
  source ./7-create_global_variable
  ```

### 8-true_knowledge

* **Description:** Adds `128` to the value stored in the environment variable `TRUEKNOWLEDGE`.
* **Usage:**

  ```bash
  export TRUEKNOWLEDGE=1209
  ./8-true_knowledge
  ```
* **Output Example:** `1337`

### 9-divide_and_rule

* **Description:** Divides the value of `POWER` by `DIVIDE`.
* **Usage:**

  ```bash
  export POWER=42784
  export DIVIDE=32
  ./9-divide_and_rule
  ```
* **Output Example:** `1337`

### 10-love_exponent_breath

* **Description:** Computes `BREATH` to the power `LOVE`.
* **Usage:**

  ```bash
  export BREATH=4
  export LOVE=3
  ./10-love_exponent_breath
  ```
* **Output Example:** `64`

### 11-binary_to_decimal

* **Description:** Converts a **binary number** from `BINARY` to decimal.
* **Usage:**

  ```bash
  export BINARY=10100111001
  ./11-binary_to_decimal
  ```
* **Output Example:** `1337`

### 12-combinations

* **Description:** Prints all possible two-letter combinations from `a-z`, except `oo`.
* **Usage:**

  ```bash
  ./12-combinations
  ```
* **Output Example:** Starts with `aa`, `ab`, …, ends with `zz` (except `oo`).

### 13-print_float

* **Description:** Prints the number stored in `NUM` with **two decimal places**.
* **Usage:**

  ```bash
  export NUM=3.14159265359
  ./13-print_float
  ```
* **Output Example:** `3.14`

### 100-decimal_to_hexadecimal

* **Description:** Converts a decimal number in `DECIMAL` to **hexadecimal**.
* **Usage:**

  ```bash
  export DECIMAL=1337
  ./100-decimal_to_hexadecimal
  ```
* **Output Example:** `539`

### 101-rot13

* **Description:** Encodes/decodes text using **ROT13 encryption**.
* **Usage:**

  ```bash
  ./101-rot13 < quote
  ```
* **Output Example:**

  ```
  "Rirelbar vf n cebcbarag bs fgebat rapelcgvba."
  ```

### 102-odd

* **Description:** Prints **every other line** from input, starting with the first.
* **Usage:**

  ```bash
  ls -1 | ./102-odd
  ```
* **Output Example:**

  ```
  bin
  dev
  home
  lib
  ```

### 103-water_and_stir

* **Description:** Adds two numbers stored in **custom-base strings** `WATER` and `STIR`, prints the result in `bestchol` base.
* **Usage:**

  ```bash
  export WATER="ewwatratewa"
  export STIR="ti.itirtrtr"
  ./103-water_and_stir
  ```
* **Output Example:** `shtbeolhc`

---

## Notes

* All scripts are written for **Ubuntu 20.04 LTS**.
* **Editors allowed:** `vi`, `vim`, `emacs`.
* All scripts are **executable**, **two lines long**, and end with a **newline**.
* **No use of `&&`, `||`, `;`, `bc`, `sed`, or `awk`** unless required by advanced tasks.

---

## Author

Eric Hackman
ALX System Engineering & DevOps
