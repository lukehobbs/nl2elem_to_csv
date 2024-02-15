# nl2elem_to_csv
Convert NoLimits2 coaster files to CSV for OpenFVD->NL2PC (without NoLimits2)

# Installation

There are two ways to install this tool:

### Option 1: Install using pip

```
pip install nl2elem-to-csv
```

### Option 2: Clone repository or download zip

1. Clone this repository or download the ZIP file.
2. If downloaded as a ZIP, extract the contents.
3. Navigate to the project directory in your terminal or command prompt.
4. Install the package locally:

```
pip install .
```

# Usage

Use the `-i` option to specify the input `.nl2elem` file and the `-o` option for the output `.csv` file path.

## Command format

```
nl2elem-to-csv -i <input_file_path> -o <output_file_path>
```

## Example

```
nl2elem-to-csv -i path/to/your/coaster.nl2elem -o path/to/your/output.csv
```
