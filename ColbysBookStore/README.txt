Colby Morgan Assignment 2

December 1, 2022
6:20
I am attempting to rebuild my assignment after an error that occured again

6:22
I've created the project, commented out the port, made a github repository, and tested to make sure it opens

6:25
changed the contents out bootsrap.css and site.css

6:28
Changed the contents of Layout.cshtml, I didn't remove "text-dark" from line 23 because in mine it didnt have any

6:31
removed text-dark from LoginPartial.cshtml and tested my website, everything looks good so far

6:35
Added links, stylesheets, and dropdown to layout.schtml
*** IMPOTANT - I need to get the rest of line 34, it is cut off in the slideshow - IMPORTANT *****

6:45
Created projects

6:55
Added all needed Frameworks

7:00
After a bit of debugging, my assignment now runs

7:12
***** ERROR *****
moved models into the project, I have an error in Views/Shared/Error.cshtml that says the type or namespace VeiwErrorModel cannot be found
in the slide show it shows them solving this by adding to the main project, project refences to the others but I have done this and I still have an error.

December 5, 2022
12:33
Got help, fixed the error by changing both references to ErrorViewModel to ColbysBookStore.Models.ViewModels.ErrorViewModel, although I'm not sure
if changing the reference in HomeContoller.cs was correct *****

12:42
added needed files to Utility project, added project references, couldn't add Models reference to DataAccess
created an error

12:51
Added files to Areas/Customer and changed namespaces

12:58
added admin area and tested all code, finished part 1 and now on to part 2

1:06
added the new migration, the file's name is 20221205180510_AddDefaultIdentityMigration

December 6, 2022
3:30
beginning todays work

3:45
I have been looking over all of the files that I can think are related to the error I am having but I am
unable to find where the issue is, for now I am going to comment out those lines and continue
until I am able to ask a classmate

4:27
I have completed the interfaces and their related classes in the Repositories folder including Repository, CategoryRepository, SP_Call, and UnitOfWork
I have the same error from before occuring on server of the files but I am hopeful that when the issue is resolved, it will resolve for eveywhere in the project
There is also another error I am having however
*****(end of 2.2) in startup.cs, line 38 - services.AddScoped<IUnitOfWork, UnitOfWork>(); - produces an error and im not sure why *****
for now I will progress with out it and hope that it can be resolved withthe other issue as well but I have a feeling that it may produce more errors in the short future
if this happens, I will have to stop progress until my code is functioning

4:46
Attempting to add the view for the next part produces an error, it states that the project must be able to build in order to procede
and since I am unable to fix my errors for now there is nothing more I can do, I am hoping that some of my classmates will be able to help,
if any show up to class today, if that fails then I will have to email my instructor and see if there is anytime for me to come in and ask questions.

December 7, 2022
5:08
somehow I managed to fix my error, I believe I forgot to specify the scope of some of my files making some of them inaccessable by the rest of my project but now my code runs

5:31
a lot of testing, I changed a few files and I have just added category.js

6:02
Added buttons for editing and delting cateogries. I noticed that some of the slides show pages that I am unable to get to using my assignemnt, I believe my navigation is broken
all I can do is continue and hope to get help with it before handing it in, its too late to restart again.

December 8, 2022
10:13
i plan on finishing part 3 and doing the final debugging of my assignment today, hopefulyl everything goes smoothly

10:57
added CoverType CRUD as well as the CoverType class, interface, and made changes to other files to allow for them

1:50
had to do some other things but I am back and I have just added the Product class as well made the changes to it

1:57
I've just added the migration, time stamp is 20221208185448_addProductToDb



2:01
in Server Object Explorer, Products table, I hae changed the contents to match what is shown in
the slideshow
**********

2:29
I've added and implemented the products interface and classes

