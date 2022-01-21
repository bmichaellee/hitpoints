# HitPoints!
HitPoints aims to be a food-tracker, video game style.

# Setting up the dev environment

**Important!**
Clone this repo with the `--recursive` flag to get
all of the submodules along with the main repo.

**Backend with Docker/VSCode**:
1. Install `docker`
2. Run `npm start` in the root directory
3. In `VSCode`, press `F1`, and select `Remote-Containers: Attach to running container ...`
4. Select `/hitpoints-api-1` from the list
5. Select `File` -> `Open Folder...` and navigate to `/usr/src/app`
6. Make edits; `localhost:8080` will update as files are saved

**Frontend**:
- **Vue**: run `npm run start:vue`
- **React**: run `npm run start:react`
- **React Native**: run `npm run start:react-native` or just `npm start`
