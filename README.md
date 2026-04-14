# Lunar PSR Improved

A web-based application for exploring and visualizing lunar permanently shadowed regions (PSRs).

## Running the Project Locally

A zip of the latest version is included in this repository.

### 1. Extract the Project

Download and extract the zip file to your desired location.

### 2. Open in VS Code

It is recommended to use Visual Studio Code.

- Open VS Code
- Click **File → Open Folder**
- Select the extracted project folder

### 3. Install Node.js

Make sure you have Node.js installed. Check by running:

```bash
node -v
npm -v
```

If not installed, download from: https://nodejs.org/

### 4. Install Dependencies

Open a terminal in VS Code (**Terminal → New Terminal**) and run:

```bash
npm install
```

### 5. Run the Development Server

```bash
npm run dev
```

### 6. Open in Browser

After running, you should see a local URL such as:

```
http://localhost:5173
```

Open that in your browser to view the application.

## Tech Stack

- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- JavaScript

## Notes

- If dependencies fail to install, try deleting `node_modules` and running `npm install` again.
- Make sure Node.js is properly installed and added to your system PATH.

## Setup Summary

```bash
npm install
npm run dev
```

## Development

Once running, any changes you make to the code will automatically update in the browser.

## Future Improvements

- Deployment (Vercel / GitHub Pages)
- Data integration for lunar datasets
- Enhanced visualization tools
