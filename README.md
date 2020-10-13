# calendarApp
The calendar App is a simple Desktop App that sorts your events into different categories which you can rank.

## setup
git clone calenderApp  
pip install poetry (if not already installed)  
poetry install (inside the folder)  
poetry run calenderApp  

## composition
The app is themed like a classical Calendar Application.
It is also connected with your google Account so you can easily access every event.
In the app you can select the desired category with a combobox.
When you read the events in another calendar the categories are marked in the description.
If two different events interfere each other, the app will ask you if you want to discard the event with the lower ranked category.
