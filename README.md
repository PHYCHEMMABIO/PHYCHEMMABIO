
**PHYCHEMMABIO/PHYCHEMMABIO** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
/* Basic Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", sans-serif;
  line-height: 1.6;
  background-color: #ffffff;
  color: #333;
}

/* Container */
.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

/* Header */
header {
  background-color: #f8f9fa;
  padding: 20px 0;
  border-bottom: 1px solid #ddd;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  float: left;
}

nav {
  float: right;
}

nav a {
  color: #333;
  text-decoration: none;
  margin-left: 20px;
  font-weight: 500;
}

nav a:hover {
  color: #007bff;
}

/* Clearfix */
header::after {
  content: "";
  display: table;
  clear: both;
}

/* Main */
main {
  padding: 40px 0;
}

/* Footer */
footer {
  background-color: #f8f9fa;
  text-align: center;
  padding: 20px 0;
  border-top: 1px solid #ddd;
  margin-top: 40px;
}
