# Welcome to BMI 203 2024

## Setting up Git and Github
### Downloading and installing git
1. Create a github account
2. Install git on your local computer <br/>
    I normally use [homebrew](https://brew.sh/) on Mac systems and install with
    ```
    $ brew install git
    ```

### Authenticating git
1. Set up git configuration
    ```
    $ git config --global user.name "Your name here"            # Add name
    $ git config --global user.email "your_email@example.com"   # Add email address
    $ git config --global color.ui true                         # Makes it easy to see what's added/staged/etc
    ```
2. Generate ssh keygen on your local computer
    ```
    $ cd       
    $ ssh-keygen -t rsa -C "your_email@example.com  # Generate keygen
    $ pbcopy < ~/.ssh/id_rsa.pub                    # Copy keygen to clipboard
    ```
3. Add key to Github.
    * On Github.com, select your user profile in the upper right corner and navigate to "Settings".
    * Navigate to "SSH and GPG keys" under "Access" in the left side bar.
    * Select the green "New SSH key" and paste the contents of your clipboarding in the "Key" box.
    * "Add SSH key" 
4. Test connection
    ```
    $ ssh -T git@github.com

    # If the output looks something like this, you're golden
    Hi username! You've successfully authenticated, but github does not provide shell access.
    ```
## Helpful resources
Learning Python 5th Edition [PDF](https://edu.anarcho-copy.org/Programming%20Languages/Python/Learning%20Python,%205th%20Edition.pdf) <br />
Bioinformatics Data Skills [PDF](https://womengovtcollegevisakha.ac.in/departments/Bioinformatics%20Data%20Skills%20Reproducible%20and%20Robust%20Research%20with%20Open%20Source%20Tools%20by%20Vince%20Buffalo.pdf) <br />
