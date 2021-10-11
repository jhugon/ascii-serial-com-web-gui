# ascii-serial-com-web-gui

A web-based GUI for ascii-serial-com

## Ideas

- Use Svelte as a frontend
- Use Python FastAPI as the backend
  - This would be an executable or script you start up that initializes the HTTP backend and serial interface
- For normal register read/write can use normal request/response
- For streaming data from the server use server sent events
