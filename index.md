<script src="https://unpkg.com/launchdarkly-js-client-sdk@2.18.1/dist/ldclient.min.js"></script>

<h1>Great LinkedIn Learning Courses</h1>

<a href='https://www.linkedin.com/learning-login/share?account=57692769&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fgit-workflows%2Fhotfixes%3Ftrk%3Dshare_video_url%26shareId%3DVVRhLZXqQKG8qv4qY2P9%252FA%253D%253D'>Link</a>

If you’re a developer working in any sort of team environment, tracking changes to a project’s source code is a vitally important aspect of the job. Git is one of the most popular tools for tracking and managing code, and there are a number of Git workflows that are commonly used by development teams for collaboration and management. In this course, Kevin Bowersox details several Git workflows that are popular with development teams. He details the main concepts behind these workflows, and shows how to choose the one that suits your needs—whether its Git Flow, GitHub Flow, or trunk-based development—to work more smoothly and eliminate pain points. If you’re looking for hands-on experience so you can work more effectively and collaboratively in Git, join Kevin in this course.

<a href="https://www.linkedin.com/learning-login/share?account=57692769&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fgit-workflows%2Fgithub-flow-in-practice%3Ftrk%3Dshare_video_url%26shareId%3DGqazX9U9QiON9%252BEBCVBrCQ%253D%253D">Link #2</a>

<div id="preview" style="display:none">
<a href="https://www.linkedin.com/learning-login/share?account=57692769&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fgit-workflows%2Freleasing-with-feature-flags%3Ftrk%3Dshare_video_url%26shareId%3DGqazX9U9QiON9%252BEBCVBrCQ%253D%253D">Link #3</a>
</div>

<script>
  var clientId = "66d885465933410fd8e942e2";
  var flagName = "course-preview";
  var user = { anonymous: true };
  var ldclient = window.LDClient.initialize(clientId, user);

  ldclient.on("ready", function () {
    document.getElementById("preview").style.display = ldclient.variation(flagName, false) ? "block": "none";
  });

  ldclient.on("change:" + flagName, function(newVal, prevVal) {
    document.getElementById("preview").style.display = newVal ? "block" : "none";
  });
  </script>