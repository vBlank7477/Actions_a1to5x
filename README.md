# Port ROM Mi A1 (Tissot) to Mi 5x (Tiffany)
 This fork ONLY WORK with roms that have boot.img system.img and vendor.img in the rom of A1
 Dont use with roms with payload.bin (check the files you gonna port)
 
**How to use a1to5x to convert a1 package into 5x usable flash package**

* Log in to your github and fork this project to your github

## Instructions
### 1. Create token
Go to your `repo settings > Developer settings > Personal access tokens > Generate new token`
- `note`: fill in RELEASE
- `Expiration`: changed to No expiration
- `Select scopes`: Check all
- `Generate token`: Click to create token
- `token`: copied token

### 2. Add secrets
Go to your `repo settings > secrets > new repository secret`
- `Name`: fill in RELEASE
- `Value`: fill in the token you just copied

### 3. Running workflow
- Go to your repo `Actions`
- Select `a1to5x` workflow (workflow)
- Open `Run workflow`
- Enter the ROM file name in `ROM NAME` (optional)
- Enter the ROM link address in `ROM LINK`
- Click the `Run workflow` button to run the workflow
