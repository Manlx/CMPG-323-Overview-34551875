<h1>
    This is the head project which will be used to document the up coming projects.
</h1>
<h2>The general rule for each project regarding the branching is:</h2>
<ul>
    <li>There are three Branches: Main/Master, Hot Fix and Development.</li>
    <li>Master/Main is the stable ready to release branch</li>
    <li>Hot fix is their for small updates to fix minor issues</li>
    <li>Development is there for feature development</li>
</ul>
<div style="display: flex; justify-content: center;">
    <img src="https://mfdot.com/Project%20Layout.svg" alt="" style="width: 500px ;height:500px">
</div>
<h2>Depending on the project the git ignore will be configured to ignore cache/compile files of said project type.
</h2>
<p>For example: For a C# Project is going to ignore the "bin","obj" folders.</p>
<h2>In most cases to secure confidential data the project will most likely implement a JSON file which will be ignored.</h2>
<p>For example: If a database log in / API key will be stored in the JSON which will NOT be on the repository.</p>
