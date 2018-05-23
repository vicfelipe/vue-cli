<script>
import firebase from 'firebase'

var config = {
    apiKey: "AIzaSyB2hPY06r5oClBFi5btdtnvsiD6FY7phlE",
    authDomain: "clact-99673.firebaseapp.com",
    databaseURL: "https://clact-99673.firebaseio.com",
    projectId: "clact-99673",
    storageBucket: "clact-99673.appspot.com",
    messagingSenderId: "148402098340"
}
var app = firebase.initializeApp(config);
var db = app.database()
var listRef = db.ref('palestrantes')

export default {
    name: 'Firebase',
    firebase: {
      listRef: listRef
    }
}
</script>

<style>

</style>
