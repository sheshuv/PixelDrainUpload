# File Upload Script

This repository contains a bash script `pup` that allows you to upload files to PixelDrain and get the URL for the uploaded files. The script checks if the file exists in the current working directory and displays the upload progress percentage.

## Features

- Upload files to PixelDrain.
- Check if the file exists from the current working directory.
- Show upload progress percentage.

## Requirements

- `curl`
- `jq`

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/sheshuv/PixelDrainUpload.git
    cd PixelDrainUpload
    ```

2. **Install Dependencies:**

    Make sure `curl` and `jq` are installed on your system.

    - On Debian/Ubuntu:

        ```bash
        sudo apt-get install curl jq
        ```

    - On macOS:

        ```bash
        brew install curl jq
        ```

## Usage

1. **Give Execute Permission:**

    Before running the script, you need to give execute permission to the script.

    ```bash
    chmod +x pup
    ```

2. **Run the Script:**

    You can run the script by providing the path to the file(s) you want to upload. You can use relative or absolute paths.

    ```bash
    ./pup /path/to/your/file1 /path/to/your/file2
    ```

    Example:

    ```bash
    ./pdlup out/target/product/benz/lineage-21.0-20240517-UNOFFICIAL-benz.zip
    ```



