# YOUTUBECLONE
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>YouTube Clone</title>
  <link rel="stylesheet" href="styles.css">
</head>
<style>
  body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background: #202020;
  color: white;
  padding: 10px 20px;
  display: flex;
  align-items: center;
  gap: 10px;
}

#search {
  flex-grow: 1;
  padding: 5px;
}

main {
  padding: 20px;
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.video-card {
  width: 300px;
  border: 1px solid #ccc;
  padding: 10px;
}

.video-card img {
  width: 100%;
}
</style>

<body>
  <header>
    <h1>YouTube Clone</h1>
    <input type="text" id="search" placeholder="Search">
    <button onclick="searchVideos()">Search</button>
  </header>

  <main id="video-container">
    <!-- Videos will appear here -->
  </main>

  <script src="script.js"></script>
</body>
</html>
