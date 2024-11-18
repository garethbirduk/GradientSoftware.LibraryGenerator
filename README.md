[<img src="https://raw.githubusercontent.com/garethbirduk/GradientSoftware.LibraryGenerator/main/resources/icon.png" width="25" height="25">](https://github.com/garethbirduk/GradientSoftware.LibraryGenerator)
[![main](https://github.com/garethbirduk/GradientSoftware.LibraryGenerator/actions/workflows/main.yml/badge.svg)](https://github.com/garethbirduk/GradientSoftware.LibraryGenerator/actions)
[![coverage](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/garethbirduk/GIST_ID/raw/code-coverage.json)](https://garethbirduk.github.io/GradientSoftware.LibraryGenerator)

# Template for dotnet projects

- [ ] GH_APIKEY - Generate this in developer settings including package creation / deletion<br>
- [ ] GIST_AUTH_TOKEN - Generate this in developer settings including gist creation
- [ ] d94eebeaba95c39761d9b3346c89c12b - Create a gist and get the d94eebeaba95c39761d9b3346c89c12b in this step
- [ ] LibraryGenerator - Repo name (without GradientSoftware.) e.g. Utils

## Generate coverage gist
https://gist.github.com/
- [ ] Set Gist description - eg code-coverage-utils.json
- [ ] Set Gist filename - eg code-coverage-utils.json
- [ ] Set Gist content - eg code-coverage-utils.json
- [ ] Note the d94eebeaba95c39761d9b3346c89c12b

# Folder level Search and Replace in files
- [ ] LibraryGenerator
- [ ] d94eebeaba95c39761d9b3346c89c12b - note d94eebeaba95c39761d9b3346c89c12b is the mask; GIST_ID is the reference to the environment variable which must remain as GIST_ID not the value!

# Rename files and folders
- [] /LibraryGenerator
- [] /LibraryGenerator/LibraryGenerator.csproj
- [] /LibraryGenerator.Test
- [] /LibraryGenerator.Test/LibraryGenerator.Test.csproj
- [] /LibraryGenerator.sln
      
# Set environment variables
https://github.com/garethbirduk/GradientSoftware.LibraryGenerator/settings/secrets/actions
- [ ] GH_APIKEY
- [ ] GIST_AUTH_TOKEN
- [ ] GIST_ID

# Set rules
https://github.com/garethbirduk/GradientSoftware.LibraryGenerator/settings/rules
- [ ] Main protection

# Github pages
https://github.com/garethbirduk/GradientSoftware.LibraryGenerator/settings/pages
- [ ] Build and deployment source: Github Actions
- [ ] Configure static page then Cancel. Not sure this is required.

