# user
user management project Sarayu Digital Labs
{
    "List": "/task-list/", # this url is for view all the task created by user
    "Detail View ": "/task-detail/<str:pk>", # this url is to see a single task created by user
    "Create": "/task-create/", # this url is to create a new task
    "Update": "/task-update/<str:pk>/", # this url is to update the existing task
    "Delete": "/task-delete/<str:pk>" # this url is to delete the existing task
}
