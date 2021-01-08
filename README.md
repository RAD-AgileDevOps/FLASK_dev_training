# FLASK_dev_training


20201-01-08

As part of the new year resolution decided to dive in to Flask training to augment my MongoDB & Python skillset

Descroption:

Using tutorial videos from  https://www.youtube.com/watch?v=k6fy7mvNSnY&list=PLcD0MjpSMpGSEsnXTKG8YvblRkazNtmJs&index=2


Mongo Collection to store training log:

MongoDB Enterprise > db.Flask_youtube_tutotials.find({}).pretty()
{
        "_id" : ObjectId("5ff829d51552358491be3109"),
        "Name" : "Introduction to HTTP - Hypertex",
        "Duration (mins)" : 6.9,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be310a"),
        "Name" : "Step 00 - Setup and Running app",
        "Duration (mins)" : 3.97,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be310b"),
        "Name" : "Step 01 - Our first Flask Webap",
        "Duration (mins)" : 3.97,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be310c"),
        "Name" : "Step 02 - Returning HTML from o",
        "Duration (mins)" : 6.3,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be310d"),
        "Name" : "Step 03 - Working with Flask/Ji",
        "Duration (mins)" : 5.47,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be310e"),
        "Name" : "Step 04 - Moving Flask/Jinja te",
        "Duration (mins)" : 4.75,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be310f"),
        "Name" : "Step 05 - Basic Routing in Flas",
        "Duration (mins)" : 6.35,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be3110"),
        "Name" : "Step 06 - Raising Custom Errors",
        "Duration (mins)" : 10.13,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be3111"),
        "Name" : "Step 07 - The Flask Request",
        "Duration (mins)" : 4.77,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be3112"),
        "Name" : "Step 08 - Flask Redirects (301,",
        "Duration (mins)" : 3.53,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be3113"),
        "Name" : "Step 09 - Plugging our first Da",
        "Duration (mins)" : 5.18,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be3114"),
        "Name" : "Step 10 - Advanced Flask and Ji",
        "Duration (mins)" : 3.08,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be3115"),
        "Name" : "Step 11 - Flask's before_reques",
        "Duration (mins)" : 3.78,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff829d51552358491be3116"),
        "Name" : "Step 12 - Using SQL JOIN in our",
        "Duration (mins)" : 2.9,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff82a971552358491be3117"),
        "Name" : "Step 13 - Working with Forms in",
        "Duration (mins)" : 5.53,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff82a971552358491be3118"),
        "Name" : "Step 14 - Working with Static F",
        "Duration (mins)" : 4.58,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff82a971552358491be3119"),
        "Name" : "Step 15 - Template Inheritance",
        "Duration (mins)" : 4.08,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff82a971552358491be311a"),
        "Name" : "Bonus - Real Class Example - Ba",
        "Duration (mins)" : 8.23,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
{
        "_id" : ObjectId("5ff82a971552358491be311b"),
        "Name" : "Bonus - Real Class Example - Wo",
        "Duration (mins)" : 18.52,
        "Completion Status" : {
                "Completed" : "No",
                "WIP" : "No",
                "Not Started" : "Yes"
        }
}
MongoDB Enterprise > db.Flask_youtube_tutotials.updateMany({"Name": {$ne: "Introduction to HTTP - Hypertex"}} , {$set: {"Completion Status.Not Started" : "Yes"}})
