# AzureML Bike-Rental

## A Machine Learning model for Bike Rentals

### Overview
This project aims to provide a machine learning solution for predicting bike rentals based on various features such as day, month, year, weather conditions, and more.

### Steps

1. **Data Preparation**: Created the dataset for training the machine learning model.

| day | month | year | season | holiday | weekday | workingday | weathersit | temp | atemp | hum  | windspeed | rentals |
|-----|-------|------|--------|---------|---------|------------|------------|------|-------|------|-----------|---------|
| 1   | 1     | 2011 | 1      | 0       | 6       | 0          | 2          | 0.344| 0.364 | 0.806| 0.16      | 331     |
| 2   | 1     | 2011 | 1      | 0       | 0       | 0          | 2          | 0.363| 0.354 | 0.696| 0.249     | 131     |

2. **Automated Machine Learning (AutoML)**: Developed an Automated ML model for learning from the data.

3. **Model Deployment**: Deployed the machine learning model and created an endpoint.

### Testing

To test the model, you can use the following JSON data:

```json
{
  "Inputs": { 
    "data": [
      {
        "day": 1,
        "month": 1,   
        "year": 2022,
        "season": 2,
        "holiday": 0,
        "weekday": 1,
        "workingday": 1,
        "weathersit": 2, 
        "temp": 0.3, 
        "atemp": 0.3,
        "hum": 0.3,
        "windspeed": 0.3 
      }
    ]    
  },   
  "GlobalParameters": 1.0
}
```
Swegger API: [Swegger API:](http://14e6b950-7368-4961-9ea2-b4aaad8d443c.brazilsouth.azurecontainer.io/swagger.json)
### Additional Notes
- **Context**: Provide a brief overview of the project, its objectives, and the potential impact it aims to achieve.
- **Interaction Instructions**: Include clear instructions for users on how they can interact with the model or deploy it in their own environments. This may involve API usage, command-line instructions, or other methods.
- **Technology Stack**: Detail the technology stack used in the project, including any dependencies, frameworks, or libraries. Additionally, provide guidance on how users can install or configure these components.
- **Consistent Formatting**: Ensure consistency in formatting and structure throughout the README for improved clarity and readability.
