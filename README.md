# Birthday Events (parents ke liye celebration page + admin)

- `/?s=Aman` : parent page (photos ke saath options, budget bar, request form)
- `/admin.html` : admin (options + photo upload, parents ki requests, status)

## Local
`npm install && ADMIN_PASSWORD=apna-password npm start` (http://localhost:3000)

## Render par (Web Service, Static Site nahi)
1. Is folder ko GitHub repo me daalo (root me `server.js`, `package.json`, `public/`)
2. Render: New -> Web Service -> repo chuno. Build: `npm install`, Start: `npm start`
3. Environment: `ADMIN_PASSWORD` = apna password
4. **Data bachane ke liye** Render Disk lagao (mount path `/var/data`) aur `DATA_DIR=/var/data` set karo.
   Free plan par disk nahi milti, redeploy/restart par photos aur requests mit jati hain.
