#333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 5px 0;
        }
        a {
            text-decoration: none;
            color: #007BFF;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Sentiments</h1>
    <ul>
        <li><a href="sentiments/file1.html">File 1</a></li>
        <li><a href="sentiments/file2.html">File 2</a></li>
        <li><a href="sentiments/file3.html">File 3</a></li>
        <!-- Add more files as needed -->
    </ul>

    <h1>Topics</h1>
    <ul>
        <li><a href="topics/file1.html">File 1</a></li>
        <li><a href="topics/file2.html">File 2</a></li>
        <li><a href="topics/file3.html">File 3</a></li>
        <!-- Add more files as needed -->
    </ul>
</body>
</html>
```

### Instructions:
1. Create a folder structure like this:
   ```
   /your-website-folder
       /sentiments
           file1.html
           file2.html
           file3.html
       /topics
           file1.html
           file2.html
           file3.html
       index.html
   ```

2. Replace `file1.html`, `file2.html`, etc., in the HTML code with the actual names of your HTML files.

3. Open `index.html` in a web browser to view the links to your HTML files.

### Automating the Process:
If you want to automate the listing of files, you would need to use a server-side language. For example, in PHP, you could use the `scandir()` function to read the directory contents and generate the list dynamically. If you're interested in that approach, let me know, and I can provide an example!