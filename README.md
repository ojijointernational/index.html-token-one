#/* Base styles */
body {
  font-family: 'Arial', sans-serif;
  background-color: #121212;
  color: #f0f0f0;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

h1, h2, h3 {
  color: #ff9800; /* Highlighted orange for headings */
}

a {
  color: #ffa726;
  text-decoration: none;
}

a:hover {
  color: #ffcc80;
}

/* Header styling */
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1em;
  background: #1e1e1e;
  border-bottom: 2px solid #ff9800;
}

.logo {
  height: 50px;
}

/* Hero section */
.hero {
  text-align: center;
  padding: 2em;
  background: linear-gradient(to bottom, #1e1e1e, #121212);
}

.hero h2 {
  font-size: 2em;
  margin-bottom: 0.5em;
}

.btn {
  padding: 0.8em 1.5em;
  background: #ff9800;
  color: #121212;
  font-weight: bold;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.btn:hover {
  background: #ffcc80;
}

/* Utility section */
.utility {
  padding: 2em;
  background: #1e1e1e;
}

.utility ul {
  list-style: none;
  padding: 0;
}

.utility li {
  margin-bottom: 0.5em;
  padding: 0.5em;
  border-left: 4px solid #ff9800;
  background: #282828;
}

/* FAQ section */
.faq {
  padding: 2em;
  background: #121212;
}

.faq ul {
  list-style: none;
  padding: 0;
}

.faq li {
  margin-bottom: 1em;
}

/* Live updates section */
.live-updates {
  padding: 2em;
  background: #1e1e1e;
  text-align: center;
}

.live-updates span {
  font-weight: bold;
  color: #ffa726;
}

/* Support section */
.support {
  padding: 2em;
  background: #121212;
}

.support p {
  margin: 0.5em 0;
}

/* Footer styling */
footer {
  text-align: center;
  padding: 1em;
  background: #1e1e1e;
  font-size: 0.9em;
  color: #888;
}

/* Responsive Design */
@media (max-width: 768px) {
  header {
    flex-direction: column;
  }

  .hero h2 {
    font-size: 1.5em;
  }

  .btn {
    padding: 0.6em 1em;
  }

  .live-updates span {
    font-size: 1.2em;
  }
} index.html-token-one
