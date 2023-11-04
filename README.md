# Packaging Python Project

- To make a package from python project, go to `packaging-tutorial` directory and follow the [python package](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

- To test your pacakge, go to `package-testing` directory, first create a virtual env by using 
```bash
python3 -m venv test
```

- Now install your pacakge that you created above using the below command,
```bash
pip install <pacakge_name>
```

and more specifically the below command for our pacakge since we uploaded it in pip test env,
```bash
python3 -m pip install --index-url https://test.pypi.org/simple/ --no-deps example-package-YOUR-USERNAME-HERE
```

for more details, see this [python package link](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

- After successfull installation of package, run the `test.py` file that is inside `package-testing` directory to use the functionality of your created package.
