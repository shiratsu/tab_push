#check push notification

%curl --header "Authorization: key=＜API KEY＞" --header Content-Type:"application/json" https://android.googleapis.com/gcm/send -d "{\"registration_ids\":[\"＜RegistrationID＞\"],\"data\":{\"message\":\"Hello\"}}"

# Reference

http://dev.classmethod.jp/smartphone/android/gcm/