# Activity 6: Setting Up a Share Folder

Three different ways to share a folder on Windows Server: Server Manager, File Explorer, and Computer Management.

## Method 1: Server Manager (folder `DEMO`)

- [ ] Create folder `DEMO` in `C:\`
- [ ] Server Manager → Files and Storage Services → Shares
- [ ] Tasks → New Share → SMB Share – Quick
- [ ] Select the server, browse to `DEMO`
- [ ] Enable access-based enumeration
- [ ] Customize permissions → Disable inheritance → Convert inherited permissions to explicit
- [ ] Remove existing permission entries, then Add → select principal `Everyone`
- [ ] Under advanced permissions, check **Create files/write data** and **Create folders/append data**
- [ ] Apply to **This folder only**
- [ ] Finish and create the share
- [ ] Verify in Server Manager → Shares that `DEMO` appears
- [ ] Check the permissions tab on the new share

## Method 2: File Explorer (folder `DEMO2`)

- [ ] Create folder `DEMO2` in `C:\`
- [ ] Properties → Sharing → Advanced Sharing
- [ ] Check "Share this folder"
- [ ] Set permissions to `Everyone`, read-only

## Method 3: Computer Management (folder `DEMO3`)

- [ ] Create folder `DEMO3-Folder` in `C:\`
- [ ] Computer Management → Shared Folders → Shares
- [ ] Right-click → New Share, point to `DEMO3-Folder`
- [ ] Customize permissions as needed

## Notes
Same end result (a shared folder), three different admin surfaces — worth knowing all three since not every environment gives you access to Server Manager.

## Screenshots to capture
- [ ] Advanced permissions for `DEMO`
- [ ] Permissions tab confirming the share
- [ ] Read-only sharing setup for `DEMO2`
- [ ] Customize permissions screen for `DEMO3`

<img width="975" height="1042" alt="image" src="https://github.com/user-attachments/assets/56d03c9d-20c3-4174-9350-161d4dc43045" />

<img width="975" height="1048" alt="image" src="https://github.com/user-attachments/assets/6bffa52b-f942-4352-bdc4-1d7a9f39dfbc" />

<img width="975" height="1052" alt="image" src="https://github.com/user-attachments/assets/1b8630d9-25eb-437b-8286-f4df492266ca" />

<img width="973" height="1041" alt="image" src="https://github.com/user-attachments/assets/b28a6774-fca5-4ec9-a340-33c5d23a2532" />

<img width="975" height="1033" alt="image" src="https://github.com/user-attachments/assets/9aed6c81-f2b2-4be7-96ed-ad814171ad9a" />

<img width="973" height="1034" alt="image" src="https://github.com/user-attachments/assets/ff187c15-1c28-4832-a295-3f9038e41b99" />

<img width="975" height="1027" alt="image" src="https://github.com/user-attachments/assets/9a6e2e1e-0e7e-4be5-b787-e2c3cd4e7717" />

<img width="973" height="1059" alt="image" src="https://github.com/user-attachments/assets/45e89764-564e-431d-9d51-df07fab32abc" />

<img width="973" height="1039" alt="image" src="https://github.com/user-attachments/assets/a76fb37e-0fc3-40a4-9069-f43b5d1f06cc" />








