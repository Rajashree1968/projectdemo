
# projectdemo
/index.html


git checkout -b create-index-html
echo "<!DOCTYPE html>
<html>
<head><title>Team Portfolio</title></head>
<body>
  <h1>Welcome to Our Team Portfolio</h1>
  <p>Content will go here.</p>
</body>
</html>" > index.html
git add index.html
git commit -m "Add index.html with basic structure"
git push origin create-index-html

/styles.css
git checkout -b create-styles
echo "body { font-family: Arial, sans-serif; background-color: #f0f0f0; } 
h1 { color: navy; }" > styles.css
git add styles.css
git commit -m "Add styles.css with initial styling"
git push origin create-styles

/script.js
git checkout -b add-js
echo "document.addEventListener('DOMContentLoaded', () => {
  alert('Welcome to the Team Portfolio!');
});" > script.js
git add script.js
git commit -m "Add script.js with alert functionality"
git push origin add-js
