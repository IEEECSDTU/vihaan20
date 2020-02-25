## Vihaan 3.0

#### To start working on this project, Please run the following commands in order

1. Download all modules needed
```
npm install
```

2. Start a dev server at http://localhost:8080/
```
npm run start
```
**NOTE**: This command will run a server at localhost:8080, which will apply all the changes you have made (or will make). However, if you want to deploy it, you need to **build** production code, follow step 3 below

3. Build file for deploying website
```
npm run build
```
**NOTE**: This command will build/combine everything (JS and CSS)  into a single **bundle.js** in **dist folder**, which is consumed by *index.html* file. Thus, this will be what you see if you open html directly without running **2nd command**. You can now deloy this project using that **bundle.js**

#### Are you looking for something?
```
home
│   README.md
│   index.html    
│
└───src
│   │   
|   └───js
|   |   |
│   |   │   index.js
|   |   |  
│   |   └─── utils
|   |
|   └───scss
|   |
|   │   index.scss
|   |  
|   └─── components   
|   |  
|   └─── fonts   
│   
└───dist
```

#### If you want to make some changes to this project, pls look into source folder, **src**, which contains *javascript* and *scss* files

##### The **index.js**, or *index.scss*, is used as main file to combine other modules or components from **utils**, or **components**, folder

## Contributor
#### Developers
* [dhruv10](https://github.com/dhruv10) - **Dhruv Bhatnagar**
* [ShivamKansal](https://github.com/ShivamKansal) - **ShivamKansal**
* [HemabhKamboj](https://github.com/HemabhKamboj) - **Hemabh Kamboj**

#### Inspiration
* [sachacks](https://sachacks.io/)