# leetlog
Simple script to log leetcode problems rather than manually keeping a spreadsheet through Google Docs or Excel

## Usage
./log <problem_number> <problem_difficulty>

## Output
Appends the following line to `leetlog.csv`:

`YYYY-mm-dd HH-MM-SS | <problem_number> | <problem_difficulty>`

### Example
`./log 760 easy`

will append the following line:

`2018-10-04 21:32:37 | 760 | easy`
