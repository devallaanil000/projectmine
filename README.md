# Call Center Data Analysis

## Project Overview
This project involves analyzing and generating insights from a call center dataset. The analysis aims to identify key trends, optimize operational efficiency, and improve customer satisfaction. The dataset contains information on call records, including agents, topics, response times, resolutions, and customer satisfaction ratings.

## Dataset Description
The dataset contains the following columns:
- **Call Id**: Unique identifier for each call.
- **Agent**: Name of the agent handling the call.
- **Date**: Date of the call.
- **Time**: Time of the call.
- **Topic**: Topic of the call (e.g., Technical Support, Contract related).
- **Answered (Y/N)**: Indicates whether the call was answered (1 for Yes, 0 for No).
- **Resolved**: Indicates whether the issue was resolved (1 for Yes, 0 for No).
- **Speed of answer in seconds**: Time taken to answer the call.
- **AvgTalkDuration**: Average duration of the call in seconds.
- **Satisfaction rating**: Customer satisfaction rating (1 to 5).
- **Weekday**: Day of the week.
- **Hour**: Hour of the day.

## Key Insights
### 1. Satisfaction Rating Distribution
- Most calls have a satisfaction rating of 3/5, indicating neutral customer experiences.
- **Action**: Investigate causes for lack of highly satisfied (5/5) ratings.

### 2. Average Talk Duration by Topic
- Topics like "Technical Support" and "Contract related" have longer talk durations.
- **Action**: Streamline agent workflows for these topics to reduce call duration.

### 3. Speed of Answer vs. Satisfaction Rating
- Calls with shorter response times (<90 seconds) generally achieve higher satisfaction ratings.
- **Action**: Set a service level agreement (SLA) target to keep response times under 90 seconds.

### 4. Call Distribution by Weekday and Hour
- Peak call volumes occur on weekdays between 9 AM-12 PM and 4 PM-6 PM.
- **Action**: Adjust staffing levels to match peak hours and optimize resource allocation.

### 5. Agent Performance Analysis
- Certain agents (e.g., "Becky" and "Diane") handle higher call volumes with consistent satisfaction ratings.
- **Action**: Identify and replicate best practices from top-performing agents.

### 6. Topics with Low Resolutions
- Topics like "Payment related" and "Technical Support" have lower resolution rates.
- **Action**: Provide additional training or resources to improve resolution rates.

### 7. Customer Pain Points
- Low satisfaction ratings correlate with long response times and unresolved issues.
- **Action**: Investigate unresolved cases and optimize agent workflows to address inefficiencies.

## Visualizations
The following visualizations were generated to support insights:
1. Distribution of satisfaction ratings.
2. Boxplot showing average talk duration by topic.
3. Boxplot showing speed of answer by satisfaction rating.
4. Heatmap showing call distribution by weekday and hour.

## Tools and Libraries
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Visualization Tools**: Seaborn and Matplotlib for graphs and charts

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/call-center-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd call-center-analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the analysis script:
    ```bash
    python analysis.py
    ```

## Folder Structure
```
call-center-analysis/
|— data/
|   — call_data.csv
|— notebooks/
|   — analysis.ipynb
|— scripts/
|   — analysis.py
|— visuals/
|   — graphs/
|— README.md
```

## Future Work
- Automate SLA compliance monitoring.
- Implement predictive models for customer satisfaction.
- Optimize staffing schedules using historical call volume data.

## Contributions
Contributions are welcome! Please fork the repository and submit a pull request for review.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

For further questions or issues, please contact [your_email@example.com].
