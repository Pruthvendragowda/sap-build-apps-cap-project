# sap-build-apps-cap-project
Full-stack SAP Build Apps + CAP project

Overview
This project demonstrates a full-stack SAP application built using SAP Build Apps (frontend) and SAP CAP (backend).

Features
- Display production orders using dynamic list (Repeat & Data Binding)
- Create new orders using form inputs
- OData API integration (GET & POST operations)
- Event-driven UI logic and navigation flow

Architecture
- Frontend: SAP Build Apps
- Backend: SAP CAP (Node.js, CDS)
- API Protocol: OData

Application Screens

Production List
[List View](PV_list_view.png)

Create Order Form
[Create Form](PV_create_form.png)

API Sample

```json
{
  "value": [
    {
      "Material": "MAT100",
      "Plant": "1000",
      "PlannedQty": 100
    }
  ]
}
