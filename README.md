
## Note!!!
- File/folder size limit is 100 MB, with a warning at 50 MB. Ensure your repository remains within these limits.
- Change gojira-tuners to your project/REPO
- Better. nah, must create new repository, clean and legit
- create new folder, copy the project folder then paste it in the new folder
- this step2 prioritized for project that have probability to have branch
  ex = main (default), admin, customer
- if there's a problem upon push, please consider to ask gpt
- consider to reset if u stuck
- use terminal


## Project Setup

### Pre-Step
1. **Set Up Git**: Ensure Git is installed on your computer. If not, download and install it from [Git's official website](https://git-scm.com).
   
2. **Create a GitHub Repository**:
   - Go to GitHub and log in to your account.
   - Click the `+` icon in the top right corner and select **New repository**.
   - Name your repository, add an optional description, choose its visibility (public or private), and click **Create repository**.

### Step 1: Clone the Repository
First, clone the empty repository to your local machine:
```bash
git clone https://github.com/Kokorody/Gojira-Tuners.git
cd Gojira-Tuners
```

### Step 2: Upload Folder to `main` Branch
1. Create and switch to the `main` branch (if not already created):
   ```bash
   git checkout -b main
   ```
   
2. Copy your folder from your local device to the repository directory:
   ```bash
   cp -r /path/to/your/local/main-folder .
   # For example, if the folder is on your desktop:
   cp -r ~/Desktop/main-folder .
   ```
   
3. Stage and commit the changes:
   ```bash
   git add main-folder
   git commit -m "Add main-folder to main branch"
   ```
   
4. Push the `main` branch to GitHub:
   ```bash
   git push -u origin main
   ```

### Step 3: Upload Folder to `admin` Branch
1. Create and switch to the `admin` branch:
   ```bash
   git checkout -b admin
   ```
   
2. Copy your folder from your local device to the repository directory:
   ```bash
   cp -r /path/to/your/local/admin-folder .
   # For example, if the folder is on your desktop:
   cp -r ~/Desktop/admin-folder .
   ```
   
3. Stage and commit the changes:
   ```bash
   git add admin-folder
   git commit -m "Add admin-folder to admin branch"
   ```
   
4. Push the `admin` branch to GitHub:
   ```bash
   git push -u origin admin
   ```

### Step 4: Upload Folder to `customer` Branch
1. Create and switch to the `customer` branch:
   ```bash
   git checkout -b customer
   ```
   
2. Copy your folder from your local device to the repository directory:
   ```bash
   cp -r /path/to/your/local/customer-folder .
   # For example, if the folder is on your desktop:
   cp -r ~/Desktop/customer-folder .
   ```
   
3. Stage and commit the changes:
   ```bash
   git add customer-folder
   git commit -m "Add customer-folder to customer branch"
   ```
   
4. Push the `customer` branch to GitHub:
   ```bash
   git push -u origin customer
   ```

### Summary of Commands
```bash
# Clone the empty repository
git clone https://github.com/Kokorody/Gojira-Tuners.git
cd Gojira-Tuners

# Set up the main branch
git checkout -b main
cp -r /path/to/your/local/main-folder .
git add main-folder
git commit -m "Add main-folder to main branch"
git push -u origin main

# Set up the admin branch
git checkout -b admin
cp -r /path/to/your/local/admin-folder .
git add admin-folder
git commit -m "Add admin-folder to admin branch"
git push -u origin admin

# Set up the customer branch
git checkout -b customer
cp -r /path/to/your/local/customer-folder .
git add customer-folder
git commit -m "Add customer-folder to customer branch"
git push -u origin customer
```

Replace `/path/to/your/local/` with the actual path to your folders on your local device. For example, if your folders are on your desktop, you might use `~/Desktop/main-folder`, `~/Desktop/admin-folder`, and `~/Desktop/customer-folder`.

GLHF!
