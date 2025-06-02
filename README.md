<img width="982" alt="Screenshot 2025-06-02 at 11 58 37" src="https://github.com/user-attachments/assets/a549a08b-9ca7-4ce0-8e89-09e71f734c55" />


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
