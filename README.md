# YOUKart-E-commerce-project-in-Django
YOUKart is E-commerce project in Django which has some basic cart functionalities like categorize products into different categories, view product description, add products to cart, payment gateway -PayTm(KEY needed to work-currently empty), product tracker(track product delivery details using order id )and it has a blog section were different blogs can be read for various products.   

# packages installed in virtial environment with there version
asgiref==3.2.10 <br>
astroid==2.4.2<br>
colorama==0.4.3<br>
Django==3.1.1<br>
isort==5.5.1<br>
lazy-object-proxy==1.4.3<br>
mccabe==0.6.1<br>
Pillow==7.2.0<br>
pycryptodome==3.9.8<br>
pylint==2.6.0<br>
pylint-django==2.3.0<br>
pylint-plugin-utils==0.6<br>
pytz==2020.1<br>
six==1.15.0<br>
sqlparse==0.3.1<br>
toml==0.10.1<br>
typed-ast==1.4.1<br>
wrapt==1.12.1<br>
No NEED TO INSTALL ALL PACKAGES.. INSTALL ONLY THOSE WHICH ARE SHOWING ERRORS...<br>

# setup 
1. Download project zip and extract it.<br>
2. Open the project folder inside visual studio code<br>
3. press ctrl + shift + p or view -> command palette and select the virtual environment name as env-cart-project.<br>
4. press <b>ctrl + shift +  `<b> --- will open terminal inside virtual environment.<br>
5. In terminal python manage.py runserver to run project.<br>
6. If error occours for package missing then install above version for that specified package.<br>
  In my case errors are solve by installing these packages (after setup for 2nd time from git)-<br>
  pip3 install pycriptodome<br>
  pip install pylint-django<br>
  pip install pillow <br>
  
# Django Tutorial in Visual Studio Code- (some common commands in use)
  Create a project virual environment for the Django tutorial.<br>
  #Windows<br>
  python -m venv env<br>
  In VS Code, open the Command Palette (View > Command Palette or (Ctrl+Shift+P)). Then select the Python: Select Interpreter command:<br>
  The command presents a list of available interpreters that VS Code can locate automatically. select the virtual environment in your project folder<br>
  
  Install Django in the virtual environment by running one of the following commands in the VS Code Terminal:<br>
  python -m pip install django<br>
  
  Create the Django project<br>
  In the VS Code Terminal where your virtual environment is activated, run the following command:<br>
  django-admin startproject web_project .<br>
  
  Create a Django app<br>
  In the VS Code Terminal with your virtual environment activated, run the administrative utility's startapp command in your project folder (where manage.py resides):<br>
  python manage.py startapp hello.<br>
  
  In the VS Code Terminal, again with the virtual environment activated, run the development server with python manage.py runserver and open a browser to http://127.0.0.1:8000/    to see a project home page<br>
  
  After modifing model files run following commands to make changes inside database<br>
  python manage.py makemigrations<br>
  python manage.py migrate<br>
  
  to accesee Django admin pannel(/admin) to make entry inside database we need to create a superuser<br>
  python manage.py createsuperuser<br>
  
  # some references to learn Django-
  https://code.visualstudio.com/docs/python/tutorial-django <br>
  https://docs.djangoproject.com/en/2.2/ref/models/fields/<br>
  https://djangobook.com/mdj2-models/ <br>
  https://docs.djangoproject.com/en/3.1/topics/db/queries/ <br>
  https://medium.com/@9cv9official/creating-a-django-web-application-with-a-postgresql-database-on-windows-c1eea38fe294 <br>
  https://wsvincent.com/django-user-authentication-tutorial-login-and-logout/ <br>
  https://books.agiliq.com/projects/django-orm-cookbook/en/latest/select_some_fields.html <br>
  https://bootsnipp.com/snippets/dldxB <br>
  
  
# screenshots (click to view in large)
<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%201.0.png" width="500" height="500"/><br>
This is the Home page were different products are shown in categories..<br> 

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%201.1.png" width="500" height="500"/>  <br>
After adding products in cart the cart is updated in right corner...we have option clear cart and proceed to checkout.<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%201.2.png" width="500" height="500"/> <br>
After proceed to checkout the next page is like this where we can see products in cart and amout to pay and a form to proceed to pay using paytm..<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%201.3.png" width="500" height="500"/>  <br>
we can search items using there name and category..<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%201.4.png" width="500" height="500"/> <br>
example:- if we search watch it will display products of watch only...<br> 

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%201.5.png" width="500" height="500"/> <br>
page occurs like this if the serach key is not match...<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%202 .png" width="500" height="500"/> <br>
Example of sorting by clicking on various categories like Electronics, men ,women...In exmaple above sorting is done using Electronics by click the Electronins button inside category navbar <br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%203.png" width="500" height="500"/> <br>
About me Page<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%204.png" width="500" height="500"/>  <br>
Example for track order using email and orderid..<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%205.png" width="500" height="500"/><br>
Home page for BLOG app....where we can access all blogs in databse..<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%206.png" width="500" height="500"/>  <br>
Example of view of perticular blog.<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%207.png" width="500" height="500"/><br>
Contact us page..<br>

<img src="https://github.com/swapnilborse42/YOUKart-E-commerce-project-in-Django/blob/master/images/screencapture%208.png" width="500" height="500"/>  <br>
After submitting contact us page
