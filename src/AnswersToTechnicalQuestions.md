Answer 1) I spent around 2.5 hours on coding.
 a) I would have added following solutions if I had enough time
   1) Implement more css and made app responsive.
   2) stored isbn values in array() using usestate hook and then mapping it to api(http://openlibrary.org/api/volumes/brief/isbn/{isbn value inserted here}.json) to get the single publish date and cover for respective volume of the book.
   3) Broken down app in more small components. For example the <button> element is used many times and could have styled the element with css module.
   

Answer 2) Sort method is one of the javascript method being used while making the application. Following is the code snippet.
let tempData = data
    tempData.docs.sort((a, b) => (a.title > b.title) ? -1 : 1)
    setData({...data,docs:tempData.docs})

Answer 3) We can track down performance issue in production by regularly load testing monitoring performance. Mainly performance issues occurs on updates which can be easily revert back and worked on.

Answer 4) API needs to be faster and needs all the cover images which are missing.

Answer 5) {
    "name":{
        "firstName": "Kanwarpal",
        "lastName": "Dhillon"
        },
    "address":{
        "street": "47 Cordgrass Crescent"
        "city": "brampton"
        "country":"Canada"
            },
    "hobbies":["soccer","reading"],
    "profession": "frontend-developer",
    "languages":["english", "hindi", "punjabi"]
    }
}