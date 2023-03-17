# Password Manager
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is the list of prerequisites needed for this password manager to run.
* Python 3.10.0+
* Pycryptodome

  ```sh
  pip install pycryptodome
  ```

### Installation & Usage


1,Go into the folder
   ```sh
   cd password-manager
   ```
 2,Run the setup script
   ```sh
   python setup.py
   ```
3,Replace the ```masterPasswordCheck``` variable in ```main.py``` with the newly generated value
   ```python
   masterPasswordCheck = "GENERATED KEY"
   ```
 4,Run the password manager and enter the master password you just used
   ```sh
   python main.py
   ```
