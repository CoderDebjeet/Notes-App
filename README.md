# Notes-App
By Making this Notes App we can learn about
*Day  1 Branch* 
1> View Model
2>Live Data
3>Room 
4>Android Architecture Component -- Activities, BroadCast Receivers, Services, Content Providers
                                Android COmponent -> Room,WorkManager,Lifecycle,Paging,Navigation,Data Binding
                                View->View Model ->Model
----------------------------------------------------------------------------------------------------------------
Making of 
1>Create Entity
2>DAO
-----------------------------------------------------------------------
*Day 2 Branch*
Insert Find Delete queries in Android Room Database
How to connect DAO with Repo and create a Singleton Room Database
1. creating our Notes schema(Model)
2. Dao creation to communicate with the database
           a.)  Making insert and delete suspend to run in a background thread rather than UI thread
            b.) Making getAllNotes List <Notes>   LiveData to get realtime changes from any Activity or fragment
3. Making a single Instance of our database using the 💥companion object  💥and use of synchronized while creating to avoid multiple threads access.

4. Creating the Repository (Single source directory to handle  all type of data like offline or online )
---------------------------------------------------------------------------------------------------------------------------------------------------------
*Day 3 Branch*
1>What is ViewModel | MVVM in Android
2>  LiveData and Observers
3> how to connect your View (Activity) with ViewModel.
---------------------------------------------------------------------------------------------------------------------------------------------------------
*Day 4 Branch*
fetch LiveData from ViewModel 
Load LiveData from ViewModel into RecyclerView
---------------------------------------------------------------------------------------------------------------------------------------------------------


*Pictorial Representation of Android Architecture Component*


![dg_architecture_comonents](https://github.com/CoderDebjeet/Notes-App/assets/91367172/24d621e2-392a-49f5-83c4-c5e0f6673d55)


