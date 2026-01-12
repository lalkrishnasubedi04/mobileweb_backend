# Digital Knowledge Network (DKN) - Backend

## Prerequisites

Before running the frontend application, ensure you have the following installed:

### Required Software

- **UV** (An extremely fast Python project manager)
  
  An extremely fast Python package and project manager, written in Rust. You can download and install it from the official website:
  
  [Download UV](https://docs.astral.sh/uv/)


## Getting Started

Follow these steps to set up and run the frontend development server:

#### 1. Clone the Repository
```bash
git clone https://github.com/lalkrishnasubedi04/mobileweb_backend.git
```

#### 2. Navigate to Backend Directory


```bash
cd mobileweb_backend
```

#### 3. Install Dependencies

```bash
uv sync
```

#### 4. Activate Virtual Environment
```bash
venv\Scripts\activate
```

#### 5. Start Development Server

```bash
uv run python3 app/main.py
```

The application will start and be accessible at the URL displayed in your terminal (typically `http://localhost:8000`).<br>
And the api documentation can be accessible at /docs URL (typically `http://localhost:8000/docs`)
