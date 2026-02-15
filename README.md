<h2>Bookmark application</h2>

Application for storing all your bookmarks for free and access it whenever you want

<h3>Tech stack used -> Next JS, tailwindCSS, supabase</h3>

Problem's faced while building the application 
-> The main problem which I faced was for having updates in real time
-> Even though I implemented the subscription setup still there was no real time update
-> I solved it by finding out that the realtime replication was not enabled in the supabase and that was the issue
-> After I toggled it ON, I now can get real time updates across tabs
