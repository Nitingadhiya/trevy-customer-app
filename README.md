# demo_web_app
flutter build web --release --web-renderer=html

### Run build command
flutter build web
firebase init hosting
 > Choose account
 > Choose public directory
    > "web/build/"
 > configure single page app
    > N 
 > Set up automatic builds and deploys with github
    > N
 > initialization complete
firebase deploy --only hosting -m "Deploying"
firebase hosting:channel:deploy e14593 
