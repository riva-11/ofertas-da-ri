body {
  background: #f9f9f9;
  color: #333;
  padding: 20px;
}

header {
  text-align: center;
  padding: 30px 0;
  background: linear-gradient(to right, #ff5722, #ff9800);
  color: white;
}

h1 {
  font-size: 2em;
}

.container {
  max-width: 1000px;
  margin: 40px auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 30px;
}

.card {
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.card img {
  width: 100%;
  height: 250px;
  object-fit: cover;
}

.card-content {
  padding: 20px;
}

.card-content h2 {
  font-size: 1.1em;
  margin-bottom: 10px;
}

.card-content p {
  font-size: 0.9em;
  margin-bottom: 15px;
  color: #666;
}

.btn {
  display: block;
  text-align: center;
  padding: 12px 20px;
  background: #ff5722;
  color: white;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s;
}

.btn:hover {
  background: #e64a19;
}

footer {
  text-align: center;
  margin-top: 60px;
  color: #999;
  font-size: 0.85em;
}
