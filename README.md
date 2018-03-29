# my-dts-workspace

A workspace template used for my project's workspace.

## Usage

### Creating a New Workspace

#### Step 0: Requirements

Install:

- [git](https://git-scm.com/)
- [nodejs](https://nodejs.org/en/)
- Any text editor

#### Step 1: Clone Git Repo

```
git clone https://github.com/JamesNgo-CoT/my-dts-workspace.git
```

#### Step 2: Remove Git Folder

Delete the __.git__ folder found at the repo's root folder.

This is to disassociate the new workspace from the repo.

Afterwards you will be able to initialize the new repo with the following command.

```
git init
```

#### Step 3: Prepare package.json

Update package.json found on the repo's root folder.

Remove everything that is __not__ under "devDependencies" and "dependencies".

Then initialize the new package with the following command.

```
npm init
```

Then install the dependencies with the following command.

```
npm install
```

#### Step 4: Done

The workspace is ready.

### Build and Serve

Build will take a project written using ES6, SCSS, NPM managed dependencies, etc, and make it backward compatible.

The following code is used to build.

```
gulp
```

Serving your built will allow you to continually test and code. To serve the project use the following command.

Changes to the source code will automatically update the built version in the dist folder.

```
gulp serve
```
