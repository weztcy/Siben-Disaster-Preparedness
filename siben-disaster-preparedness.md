# Portfolio Project Data — Siben - Disaster Preparedness

- **Category:** `web-development` (`Web Development`)
- **Accent Color:** `cyan`
- **Target Assets Folder:** `public/images/projects/siben_disaster_preparedness/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image05.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "siben-disaster-preparedness",
  "code": "PRO-18 // WEB-05",
  "title": "Siben - Disaster Preparedness",
  "category": "web-development",
  "categoryLabel": "Website",
  "year": "2023",
  "status": "Completed",
  "accentColor": "cyan",
  "repoUrl": "https://github.com/weztcy/Siben-Disaster-Preparedness",
  "license": "MIT License",
  "banner": "/images/projects/siben_disaster_preparedness/banner.webp",
  "summary": "Full-stack disaster preparedness platform uniting mitigation guides, MySQL incident CRUD, disaster news, and live BMKG Semarang weather forecasts.",
  "projectDescription": "Siben is a full-stack disaster preparedness web platform built with React, Redux, Express, and MySQL. It combines ten interactive hazard mitigation guides, paginated disaster incident CRUD management, curated national disaster news, and a live BMKG Semarang weather forecast proxy.",
  "architectureSummary": "React and Redux SPA communicating via Axios with an Express REST API backed by Sequelize MySQL persistence and a BMKG weather proxy.",
  "techStack": [
    "JavaScript",
    "React",
    "Redux",
    "Redux Thunk",
    "React Router",
    "React Bootstrap",
    "Bootstrap",
    "Axios",
    "Node.js",
    "Express",
    "Sequelize",
    "MySQL"
  ],
  "telemetryMatrix": {
    "projectType": "Full-Stack Web Application",
    "targetPlatform": "Web Browser & REST API",
    "primaryDomain": "Disaster Preparedness & Mitigation",
    "architecturePipeline": "React Redux -> Express API -> MySQL",
    "testingAndAudit": "Manual UI & API Verification",
    "projectStatus": "Completed",
    "projectYear": "2023"
  },
  "projectInfo": {
    "projectType": "Full-Stack Web Application",
    "developmentStatus": "Completed",
    "developmentYear": "2023",
    "platform": "Web Browser",
    "projectCategory": "Web Development"
  },
  "projectBackground": "Public disaster literacy and timely incident tracking are critical across Indonesia's hazard-prone regions. Siben addresses fragmented access to emergency preparedness procedures, historical casualty records, and regional weather advisories by unifying educational mitigation workflows with a centralized data portal.",
  "problemStatements": [
    {
      "title": "Fragmented Hazard Preparedness Guidance",
      "description": "Public safety procedures across diverse natural disasters are often scattered, making rapid pre-disaster, response, and recovery checklists difficult to navigate.",
      "issueCode": "ISSUE_01"
    },
    {
      "title": "Manual Incident Record Tracking",
      "description": "Tracking regional disaster occurrences, casualty counts, and root causes requires structured CRUD workflows with persistent relational storage and pagination.",
      "issueCode": "ISSUE_02"
    },
    {
      "title": "Disconnected Meteorological Advisories",
      "description": "Users monitoring disaster risks need direct visibility into localized weather forecasts and agency locations without switching across external portals.",
      "issueCode": "ISSUE_03"
    }
  ],
  "projectObjectives": [
    {
      "title": "Standardize Ten Hazard Mitigation Workflows",
      "description": "Deliver dedicated interactive routes for ten major natural disasters with structured offcanvas topic drawers and three-stage lifecycle accordions.",
      "targetTag": "TARGET_01"
    },
    {
      "title": "Centralize Relational Disaster CRUD",
      "description": "Implement a Sequelize and MySQL REST API supporting chronological sorting, modal creation and editing, deletion, and configurable table pagination.",
      "targetTag": "TARGET_02"
    },
    {
      "title": "Proxy Live BMKG Weather Data",
      "description": "Normalize official BMKG Semarang Tengah forecast feeds on the backend to display timestamped conditions, humidity, and dual Celsius/Fahrenheit metrics.",
      "targetTag": "TARGET_03"
    }
  ],
  "coreFeatures": [
    {
      "title": "Ten Hazard Preparedness Subpages",
      "description": "Dedicated React Router views for Earthquake, Tsunami, Volcano, Flood, Landslide, Cyclone, Drought, Wildfire, Heatwave, and Thunderstorm with offcanvas drawers and phase accordions.",
      "badge": "Education"
    },
    {
      "title": "MySQL Disaster Record CRUD",
      "description": "Paginated dark-themed table with configurable page size (5, 10, 20, 50), province and hazard dropdowns in add/edit modals, and instant Redux state refresh.",
      "badge": "Data Management"
    },
    {
      "title": "BMKG Semarang Weather Proxy",
      "description": "Backend /weather endpoint querying BMKG adm4 33.74.01.1001, flattening multi-day forecasts, computing Fahrenheit equivalents, and rendering glassmorphic cards.",
      "badge": "Weather API"
    },
    {
      "title": "Curated Disaster News & Agency Maps",
      "description": "Express /news feed rendering regional incident coverage alongside embedded Google Maps views for BNPB headquarters and BMKG Semarang.",
      "badge": "Information"
    }
  ],
  "interfaceShowcase": [
    {
      "imageUrl": "/images/projects/siben_disaster_preparedness/image01.webp"
    },
    {
      "imageUrl": "/images/projects/siben_disaster_preparedness/image02.webp"
    },
    {
      "imageUrl": "/images/projects/siben_disaster_preparedness/image03.webp"
    },
    {
      "imageUrl": "/images/projects/siben_disaster_preparedness/image04.webp"
    },
    {
      "imageUrl": "/images/projects/siben_disaster_preparedness/image05.webp"
    }
  ],
  "userFlow": {
    "summary": "Users navigate from the landing hub into four core modules: ten hazard mitigation subpages featuring offcanvas safety guides and three-phase accordions, a paginated MySQL-backed disaster CRUD table with modal forms, a national disaster news feed, and a live BMKG Semarang weather forecast grid.",
    "steps": [
      {
        "step": "01",
        "title": "Explore Landing Hub & Navigation",
        "description": "Users open the Home hub to inspect overview cards, read the modal introduction, view the three-stage disaster lifecycle carousel, or select modules from the navbar.",
        "actorOrNode": "Home / NavigationBar"
      },
      {
        "step": "02",
        "title": "Consult Hazard Mitigation Guides",
        "description": "Users select any of the ten disaster types to open offcanvas drawers (causes, structure, types, impacts, tips) and expand mitigation, response, and recovery accordions.",
        "actorOrNode": "Penanganan / SubPenanganan"
      },
      {
        "step": "03",
        "title": "Manage Disaster Incident Records",
        "description": "Users paginate through chronological disaster rows, adjust page size, or submit add, edit, and delete requests that synchronize Redux state with MySQL.",
        "actorOrNode": "DataBencana / Express API"
      },
      {
        "step": "04",
        "title": "Review News & Live Semarang Weather",
        "description": "Users browse curated disaster news articles and inspect live BMKG Semarang forecast cards alongside embedded BNPB and BMKG maps.",
        "actorOrNode": "Berita / WeatherCard"
      }
    ]
  },
  "systemArchitecture": {
    "summary": "The application follows a decoupled client-server architecture where a React and Redux frontend communicates over HTTP via Axios with an Express REST API. The backend handles Sequelize ORM persistence in MySQL, serves curated disaster news, and proxies live BMKG meteorological data.",
    "layers": [
      {
        "name": "Presentation & Routing Layer",
        "role": "Renders responsive React Bootstrap views, ambient video backgrounds, offcanvas safety drawers, CRUD modals, and 15 client routes.",
        "components": ["App Router", "Page Modules", "Reusable UI Components"]
      },
      {
        "name": "Client State & Networking Layer",
        "role": "Manages asynchronous loading, payload caching, and error states for disaster records and weather forecasts using Redux Thunk and Axios.",
        "components": ["Redux Store", "Disaster Actions & Reducer", "Weather Actions & Reducer"]
      },
      {
        "name": "REST API & Proxy Layer",
        "role": "Exposes CORS-enabled Express endpoints for disaster CRUD, news retrieval, and BMKG public weather normalization.",
        "components": ["Express Server", "Disasters Controller Routes", "BMKG Weather Proxy"]
      },
      {
        "name": "Relational Persistence Layer",
        "role": "Stores and migrates structured Indonesian disaster records sorted chronologically in MySQL via Sequelize ORM.",
        "components": ["Sequelize ORM", "Disaster Model", "MySQL databencana"]
      }
    ]
  },
  "databaseDataFlow": {
    "type": "Database Schema & API Pipeline",
    "summary": "Sequelize manages the Disasters table in the MySQL databencana database with historical Indonesian seeding, while Express also serves structured news articles and flattened BMKG weather forecast records.",
    "entitiesOrPipelines": [
      {
        "name": "Disasters",
        "type": "MySQL Table",
        "fields": [
          "id",
          "tanggal_bencana",
          "provinsi",
          "kota_kabupaten",
          "alamat_lokasi",
          "bencana_alam",
          "penjelasan_penyebab",
          "korban_jiwa",
          "createdAt",
          "updatedAt"
        ]
      },
      {
        "name": "NewsArticles",
        "type": "API Dataset",
        "fields": ["id", "date", "title", "imageUrl", "author", "linkUrl"]
      },
      {
        "name": "WeatherForecast",
        "type": "BMKG Proxy Payload",
        "fields": ["jamCuaca", "cuaca", "kodeCuaca", "humidity", "tempC", "tempF", "imageUrl"]
      }
    ]
  },
  "technicalImplementation": [
    {
      "category": "State Management",
      "title": "Redux Thunk Async Synchronization",
      "description": "Separates disaster and weather slices via combineReducers, dispatching request, success, and failure actions upon Axios completion and re-fetching after CRUD mutations.",
      "badge": "Redux Thunk"
    },
    {
      "category": "External API Normalization",
      "title": "Server-Side BMKG Forecast Flattening",
      "description": "The /weather route fetches nested multi-day forecast arrays from api.bmkg.go.id for Semarang Tengah, flattens entries, and derives Fahrenheit temperatures server-side.",
      "badge": "API Proxy"
    },
    {
      "category": "Database & Seeding",
      "title": "Sequelize Schema Migration & Historical Seeder",
      "description": "Defines explicit Sequelize migrations and a 20-plus year Indonesian disaster seeder ordered by tanggal_bencana DESC for consistent chronological table rendering.",
      "badge": "Sequelize ORM"
    },
    {
      "category": "UI Architecture",
      "title": "Configurable Pagination & Offcanvas Content Injection",
      "description": "Implements dynamic page-size slicing (5 to 50 rows) in DataBencana alongside reusable BencanaOffcard and KontenBencanaCard templates across ten hazard pages.",
      "badge": "React Bootstrap"
    }
  ],
  "primaryTechSpecs": {
    "programmingLanguage": "JavaScript",
    "framework": "React & Express",
    "database": "MySQL"
  },
  "architectureQuality": {
    "badges": [
      "Modular React UI",
      "Redux State Store",
      "Sequelize ORM Layer",
      "BMKG Weather Proxy"
    ]
  }
}
```
