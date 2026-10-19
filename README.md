# Shell Scripting - Day 2 Machine Test

## Student Details

- **Student Name:** Boby
- **Batch:** 9:15 PM
- **Date:** 10/14/2026

## Scripts

| Script | Description |
|--------|-------------|
| `company.sh` | Declares the company name as a `readonly` variable and prints it. |
| `deployment.sh` | Prompts for an application name and environment using `read -p`, then prints them with a "Deployment Started" message. |
| `devops_registration.sh` | A DevOps registration portal that collects candidate name, technology, batch and preferred environment, then prints a formatted confirmation. |
| `employee.sh` | Reads the employee name and employee ID in a single `read` prompt and displays both values. |
| `login.sh` | Reads a username and a hidden password (`read -s`), then confirms the login was captured and prints only the username. |
| `personal_info.sh` | Collects name, age and city from the user and prints them under a "User Details" heading. |
| `server_registration.sh` | Accepts a server name and environment and prints the registration details. |
| `student_registration.sh` | Collects student name, course and batch, then prints a formatted "Student Registration Details" summary. |
| `system_info.sh` | Uses command substitution to show the current user (`whoami`), date (`date`) and working directory (`pwd`). |
| `userinfo.sh` | Displays the current user, home directory (`$HOME`) and default shell (`$SHELL`). |

## How to Run

```bash
chmod +x script_name.sh
./script_name.sh
```

Or run it directly with bash:

```bash
bash script_name.sh
```

## Repository Structure

```
shell-scripting-day2-machine-test/
├── company.sh
├── deployment.sh
├── devops_registration.sh
├── employee.sh
├── login.sh
├── personal_info.sh
├── server_registration.sh
├── student_registration.sh
├── system_info.sh
├── userinfo.sh
└── README.md
```
