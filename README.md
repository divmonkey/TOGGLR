# TOGGLR — Server Manager

A beautiful, modern web-based server management dashboard for monitoring and controlling multiple development servers.

## 📋 Overview

TOGGLR is a real-time server monitoring and management tool that provides a sleek interface to:
- **Monitor server status** (online/offline)
- **View real-time metrics** (CPU, memory, uptime, port information)
- **Manage processes** (start/kill servers with one click)
- **Explore file locations** (browse server files and configurations)
- **Track GPU usage** (view top applications consuming GPU)
- **Filter & search** (quickly find servers by name, description, or port)

Perfect for developers managing multiple local development servers, microservices, and background processes.

## 🎯 Features

### Server Management
- **14 Pre-configured Servers**: Node.js, Mailpit, Redis, PostgreSQL, MySQL, MongoDB, Nginx, Django, PHP, MinIO, Memcached, Elasticsearch, RabbitMQ, and Vite
- **Status Indicators**: Real-time online/offline status with visual indicators
- **Port Management**: Click ports to access servers directly
- **Force Kill**: Instantly terminate processes with confirmation protection
- **Start Servers**: Resume offline servers with one click

### Real-time Monitoring
- **System Information**: CPU cores, RAM, storage, and architecture
- **Uptime Tracking**: See how long each server has been running
- **Memory Usage**: Monitor real-time memory consumption per process
- **Process IDs**: View PID for each running server

### File Browser
- **File Exploration**: Browse server files and configurations
- **File Categories**: Config, logs, data, source code, binaries, sockets, locks, certificates, and more
- **Quick Access**: Reveal file locations in your file explorer/terminal

### GPU Monitoring
- **GPU Detection**: Auto-detects your graphics card
- **Real-time Usage**: Track GPU percentage utilization
- **Top Apps**: See which 5 applications are consuming the most GPU

### Search & Filter
- **Quick Search**: Filter servers by name, description, or port
- **Status Tabs**: View all, online, or offline servers
- **Live Counting**: Real-time server count updates

## 🚀 How to Use

### Getting Started

1. **Open in Browser**
   ```bash
   # Simply open the HTML file in any modern browser
   # No installation or build process required
   ```

2. **Main Dashboard**
   - View all servers at a glance
   - See online (green) vs offline (gray) status
   - Check system specifications and GPU usage in the header

### Managing Servers

**Starting a Server**
1. Click the **START** button on an offline server
2. Server transitions to "starting" state
3. Once online, you can access it via the port link

**Stopping a Server**
1. Click the **FORCE KILL** button on an online server
2. Confirm by clicking **CONFIRM** within 4 seconds
3. Server will transition to offline state

**Kill All Online Servers**
- Use the **Kill All** button in the top-right to terminate all servers at once
- Useful for a clean system reset

### Viewing Server Details

**Files & Configuration**
1. Click **View files** on any running server
2. Browse all associated files and configurations
3. Click **Reveal** to open file locations in your OS file explorer

**Server Information**
- **Port**: Click to access the server in your browser
- **PID**: Process ID of the running server
- **Memory**: Current memory consumption
- **Uptime**: How long the server has been running

### Searching & Filtering

**Search for Servers**
- Use the search box to filter by server name, description, or port
- Results update in real-time

**Filter by Status**
- **All**: View all servers
- **Online**: View only running servers
- **Offline**: View only stopped servers

### GPU Monitoring

**View GPU Usage**
1. Check the GPU widget in the top-right
2. See your graphics card model and current usage percentage
3. Click **Top GPU Apps** to see which 5 applications are using the most GPU

## 🛠️ Technical Details

- **Pure Frontend**: Built with vanilla JavaScript (no dependencies required)
- **Modern UI**: Tailwind CSS for styling with custom animations
- **Icons**: Font Awesome 6.5.0 for beautiful icons
- **Responsive**: Works on desktop, tablet, and mobile devices
- **Performance**: Smooth animations and real-time updates with zero latency

## 📦 File Structure

```
server-manager/
├── index.html          # Main application (everything in one file)
└── README.md          # This file
```

## 🎨 Features Coming Soon

This project is actively under development. Upcoming features include:

- 🔌 **Real Backend Integration**: Connect to actual system processes
- 📊 **Historical Graphs**: Track metrics over time
- 🔔 **Alerts & Notifications**: Get notified when servers go down
- 🔐 **Authentication**: Secure access with login
- 📱 **Mobile App**: Dedicated mobile application
- 🐳 **Docker Support**: Monitor containerized services
- 🌐 **Remote Servers**: Manage servers across multiple machines
- 💾 **Persistent Storage**: Save configurations and preferences
- 📋 **Custom Commands**: Add custom scripts and commands
- 🎯 **Server Groups**: Organize servers into logical groups

## 💻 Browser Compatibility

- ✅ Chrome/Chromium (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Requires modern browser with ES6+ support

## 🤝 Contributing

This is a personal project in active development. Feel free to fork and create your own version!

## 📝 License

MIT License - Use freely for personal and commercial projects

## 👤 Author

**Joseph Oracoy** - Creator of TOGGLR

---

**Note**: TOGGLR is currently showing simulated server data. Real backend integration and live system monitoring coming soon!
