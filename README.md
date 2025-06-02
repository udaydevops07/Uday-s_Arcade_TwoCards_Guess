📁 Folder Structure

Uday-s_Arcade_TwoCards_Guess/
├── Dockerfile
├── index.html
└── nginx.conf

✅ Step 1: Save your HTML
Save your HTML as index.html in a folder called

✅ Step 2: Create nginx.conf
This configuration tells Nginx to serve your HTML file from the root.

✅ Step 3: Create Dockerfile

✅ Step 4: Build and Run

# Build the image
docker build -t uday-arcade .

# Run the container
docker run -d -p 8080:80 uday-arcade
Then open your browser at:
👉 http://localhost:8080
