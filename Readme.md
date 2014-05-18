#Grails, Bootstrap and the sass-asset-pipeline.

This is a very minimal Grails application demonstrating how to use the sass-asset-pipeline.

Note: Currently this app uses the new Grails 2.4.0.RC2 pre-release, I'll probably update it to the release when it comes out.

I really only had two requirements.

  * Use sass.  There wasn't a grails plugin for bootstrap-sass and I wanted to see how easy it 
  was to use the sass version without needing to create a plugin. 
  * I wanted to clearly separate the files in the bootstrap-sass distribution from my own customization.

Most of the configuration comes from just laying out files correctly in the grails-app/assets folder.  I chose to add a 
new vendor folder as a peer to the existing javascripts and stylesheets folders.  My plan is to put all of my vendor or 
third-party js or css libraries under there.

I tried to keep the commit history clean so if you look back you should be able to see exactly what changes are what.
