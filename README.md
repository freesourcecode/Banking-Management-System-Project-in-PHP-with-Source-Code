# CRUD in CodeIgniter using Ajax with Source Code

**CRUD in CodeIgniter Using Ajax** is an acronym that comes from the world of computer programming.

It stands for “**create**, **read**, **update**, and **delete**,” which are the four things that are needed to make a persistent storage application work.

The **CRUD in CodeIgniter Using Ajax stands for (Create, Read, Update, and Delete)**, Get a basic understanding of how to work with **CodeIgniter** by using this CRUD In CodeIgniter 4.

This is extremely useful for folks who are new to PHP programming. This web application also makes use of the Bootstrap Library to provide a pleasant user interface and a better user experience for end-users.

A **CRUD in CodeIgniter with Bootstrap** is widespread in the application of knowledge with the Database’s basic **CREATE**, **READ**, **UPDATE**, and **DELETE** functionality.

## What is CodeIgniter?

**CodeIgniter** is an Application Development Framework – a toolset – for PHP website developers.

Its purpose is to let you construct projects much faster than if you were programming code from the start by providing a rich set of libraries for common activities, as well as a simple interface and logical structure to access these libraries.

By reducing the amount of code required for a given operation, CodeIgniter allows you to focus more creatively on your project.

This CRUD In CodeIgniter also includes a downloadable CRUD Operation free source code, just find the downloadable source code below and click to start downloading.

## How to Run the CRUD in CodeIgniter using Ajax?

These are the steps on **how to run CRUD in CodeIgniter Using Ajax with Source Code**.

1. **Download Source Code**

2. **Extract File**

After finishing downloading the file, go to the file location right-click the file and click extract.

![image](https://github.com/user-attachments/assets/ca01371b-490f-4c77-92c1-fa2ccfc0d968)

3. **Copy Project Folder**

Copy the project folder and paste it to C:\xampp\htdocs.

4. **Open Xampp**

Open **xampp** and start the **Apache** and **mysql**.

![image](https://github.com/user-attachments/assets/82f678b2-a0ec-4603-97e3-6c8ec6e3dcd2)

5. **Create Database**

Click any browser type the URL localhost/phpmyadmin, and create a database.

![image](https://github.com/user-attachments/assets/b4052a7a-0069-466a-bfe8-44f19999a38e)

6. **Import Database**

Click the created database, click import to the right tab, click Choose File, and import the sql file inside the download folder.

![image](https://github.com/user-attachments/assets/95255277-51d1-4fff-83ab-f79a419baf8a)

7. **Execute Project**

Final, type to the URL localhost/codeigniter_crud.

## How to Create CRUD Operations in CodeIgniter?

The code given below is for the user list module

* **views: user_list.php** :


```
<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
	<title>CodeIgniter Simple CRUD (IT SOURCECODE)</title>
	<link rel="stylesheet" type="text/css" href="<?php echo base_url(); ?>bootstrap/css/bootstrap.min.css">
</head>
<body class="bg-info">
<div class="container">
	<h1 class="page-header text-center">CodeIgniter Simple CRUD (IT SOURCECODE)</h1>
	<div class="row">
		<div class="col-sm-8 col-sm-offset-2">
			<a href="<?php echo base_url(); ?>index.php/users/addnew" class="btn btn-success"><span class="glyphicon glyphicon-plus"></span> Add New</a><br><br>
			<table class="table table-bordered table-striped">
				<thead>
					<tr>
						<th>ID</th>
						<th>Username</th>
						<th>Password</th>
						<th>FullName</th>
						<th>Action</th>
					</tr>
				</thead>
				<tbody>
					<?php
					foreach($users as $user){
						?>
						<tr>
							<td><?php echo $user->id; ?></td>
							<td><?php echo $user->email; ?></td>
							<td><?php echo $user->password; ?></td>
							<td><?php echo $user->fname; ?></td>
							<td><a href="<?php echo base_url(); ?>index.php/users/edit/<?php echo $user->id; ?>" class="btn btn-success"><span class="glyphicon glyphicon-edit"></span> Edit</a> || <a href="<?php echo base_url(); ?>index.php/users/delete/<?php echo $user->id; ?>" class="btn btn-danger"><span class="glyphicon glyphicon-trash"></span> Delete</a></td>
						</tr>
						<?php
					}
					?>
				</tbody>
			</table>
		</div>
	</div>
</div>
</body>
</html>

```

* **User List Output**:

![image](https://github.com/user-attachments/assets/c1c7ecd6-fa5b-4446-9897-8dbc97ec2920)

### 📌Full documentation for the CRUD in CodeIgniter using Ajax is available at: ⬇️⬇️⬇️

https://itsourcecode.com/free-projects/php-project/crud-in-codeigniter-using-ajax-with-source-code/







