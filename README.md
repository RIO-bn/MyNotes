# MyNotes
MyNotes is a lightweight web application built using C# and ASP.NET Framework that allows users to create, edit, and manage notes securely.
It features user authorization, ensuring that each user can only access their own notes.
The project also provides a RESTful API for integration with other applications or frontend clients.

1. Clone the repository
git clone https://github.com/<your-username>/MyNotes.git

Open the project

Open Visual Studio 2022 (or later).

Go to File → Open → Project/Solution.

Select the MyNotes.sln file.

Update-Database

If you don’t have migrations yet, you can generate them:

Add-Migration InitialSetup
Update-Database

Press F5 or click Start Debugging.

The app will start on https://localhost:<port>/
