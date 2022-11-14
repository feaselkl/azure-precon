# Operations

1. Make sure packages are installed.

    `pip install wheel`

    `pip install check-wheel-contents`

2. Build the package.

    `python setup.py bdist_wheel`

3. Check the results.

    `check-wheel-contents .\dist\`

4. Upload to Synapse workspace and assign to Spark pool.
