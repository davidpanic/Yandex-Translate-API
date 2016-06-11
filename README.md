# Yandex-Translate-API
This is an api for using the yandex translate engine in java.

# Usage:
- private request(String URL):
  Used within the code, to request stuff from the server, does not need to be used outside the TranslateAPI class.

- getLangs():
  used to get the currently available languages from the yandex api server, look at Example.java for further information.

- translate(String text, String sourceLang, String targetLang):
  Used to translate strings of text, look at Example.java for further information.

- detectLanguage(String text):
  Used to detect the language of a string.

- getKey(Map<String, String> map, String value):
  Used to get the short name of a language from a string aka: "english" -> "en"
