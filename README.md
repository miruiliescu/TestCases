# Test Case Samples using Qase

Below are some Test Case samples that I wrote while working on previous projects.


-----------------------


**Description:**
Check if the login works when user enters the correct credentials.

**Steps to reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add correct user/pass
3. Click login button

**Expected result:**
User should be able to login and is redirected to his profile page.


**Test data:**
User: miruna
Pass: 123

**Pre-conditions:**
User should have a valid account.


-----------------------

**Description:**
Check if the login fails when a user enters the incorrect credentials.

**Steps to reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add incorrect user/pass
3. Click "Login" button

**Expected result:**
User should not be able to login.

**Test data:**
User: miruu
Password: 122


-----------------------


**Description:**
Check if the login fails when a user doesn't enter the credentials.

**Steps to reproduce:**
1. Go to https://auth.emag.ro/user/login
2. Click "Login" button

**Expected result:**
The user should not be able to login.

-----------------------


**Description:**
Check if the "Search" button opens search results after a client adds a search query.

**Steps to reproduce:**
1. Open emag.ro/#opensearch
2. Add search query
3. Click "Search" button

**Expected result:**
Client is provided with search result pages based on the query that was typed. In this case, it will show multiple GoPro models and accessories.

**Test data:**
Query: GoPro


------------------------


**Description:**
Check if query autocompletes when the user is typing inside the search bar.

**Steps to reproduce:**
1. Open emag.ro/#opensearch
2. Type the first three letters of the query "gopro"

**Expected results:**
Query should autocomplete after the first three letters are typed.

**Test data:**
Query: gopro


---------------------------


**Description:**
Check if the app sends an error when searching for an item that doesn't exist.

**Steps to reproduce:**
1. Open emag.ro/#opensearch
2. Type inside the search bar the given query
3. Click the search button

**Expected results:**
The website should open a new page showing "0 results found" for the searched item.

**Test data:**
Query: dddddddd.
