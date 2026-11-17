# Split a List into Groups

A small Python program that takes a list of numbers and splits it into groups of a size you choose. If the list doesn't divide evenly, the last group simply holds whatever is left.

Written as part of my Python practice while studying data analytics.

---

## How It Works

1. The program starts with a list of numbers.
2. It asks you for a group size.
3. It walks through the list in steps, slicing out one group at a time.
4. Each group is printed on its own line.

If the size is less than 1, the program lets you know instead of running.

---

## Example

**Input**

```
Enter group size: 3
```

**Output**

```
[1, 2, 3]
[4, 5, 6]
[7]
```

With a group size of `2`:

```
[1, 2]
[3, 4]
[5, 6]
[7]
```

With an invalid size:

```
Enter group size: 0
size must be at least 1
```

---

## Run It

Make sure Python 3 is installed, then run:

```bash
python split_list.py
```

---

## What I Practiced

- Slicing lists with `numbers[start:start + size]`
- Using a `while` loop with a moving start position
- Reading input and converting it with `int()`
- Handling invalid input with a simple `if / else` check

---

## Possible Improvements

- Handle non-numeric input without crashing
- Let the user enter their own list
- Move the logic into a reusable function

---

## About me

**Rammal Ahmed**

**AI & Data Science Enthusiast** | **Microsoft Dynamics 365 CRM Developer** | **Power Platform** | **UI/UX Designer** | **Graphic Designer & Illustrator**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rammal-ahmed-58184b325)
[![GitHub](https://img.shields.io/badge/GitHub-Rammal--Ahmed-181717?style=flat&logo=github)](https://github.com/Rammal-Ahmed)

<div align="center">

If you found this useful, consider giving it a star ⭐

**I truly value your feedback and welcome any suggestions for improvement**

**Always open to fresh perspectives, constructive feedback, and new ideas**


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details

---

*Developed as part of my Python programming practice*

---

**Project Status:** Completed

</div>
