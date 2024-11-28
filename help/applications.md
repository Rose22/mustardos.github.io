# Applications

There is a special Applications menu on the home screen. This Applications menu is preloaded with a bunch of useful apps!

It is extensible. You can download more apps off of the muOS discord. You can simply install them using the Archive Manager. They will then show up under the Applications menu!

# Creating Applications for muOS
If you want to create your own Application, the structure is as such:
```
SD1
└─ MUOS
    └── application
        └── YourApp.sh
        └── .yourapp
            ├── <application files>
```

YourApp.sh is the launch script for your application, and must contain all the necessary code for the launch to function properly. 

Take a look at the code of existing launch scripts within the application folder, to learn how to create your own.
