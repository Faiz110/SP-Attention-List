{
  "$schema": "https://developer.microsoft.com/json-schemas/sp/v2/row-formatting.schema.json",
  "hideSelection": true,
  "hideColumnHeader": true,
  "hideListHeader": true,
  "rowFormatter": {
    "elmType": "div",
    "style": {
      "margin": "8px 0",
      "border": "1px solid #ddd",
      "border-radius": "6px",
      "box-shadow": "0 1px 3px rgba(0,0,0,0.1)",
      "overflow": "hidden",
      "max-width": "900px"
    },
    "children": [
      {
        /* Accordion Header (Question) */
        "elmType": "div",
        "style": {
          "padding": "10px 14px",
          "font-weight": "600",
          "font-size": "15px",
          "cursor": "pointer",
          "background-color": "#f3f2f1",
          "color": "black"
        },
        "attributes": {
          "class": "sp-row-accordionHeader"
        },
        "txtContent": "[$Question]"
      },
      {
        /* Accordion Body (Answer) */
        "elmType": "div",
        "style": {
          "padding": "10px 14px",
          "font-size": "14px",
          "display": "none",
          "background-color": "white",
          "color": "black"
        },
        "attributes": {
          "class": "sp-row-accordionBody"
        },
        "txtContent": "[$Answer]"
      }
    ]
  }
}
