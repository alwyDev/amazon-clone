This is a simple Amazon Clone website created with ReactJS and firebase authentication login

live deployed website https://clone-ab2fb.web.app/

note for me:
1. 'npm run start' to run the localhost.
2. 'npm run build ' then 'firebase deploy' in terminal to deploy. after that just commit and push to git.
3. Open new terminal, enter 'cd functions' and then 'firebase emulators:start' to start the firebase emulator and activate localhost for the backend. This act is needed to run the Payment Process with Stripe. It works like this because the base URL for backend is still using localhost (located in axios.js). Upgrade the firebase to Blaze to solve this problem.