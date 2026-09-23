V22 HARD FIX
The screenshots showed the language text changed but the image assets did not, which means the browser was executing cached/old asset behavior.
Fixes:
1. hard cache-bust for app-v15.js;
2. every language asset URL gets ?v22;
3. direct src swap on language change;
4. feature label images forced visible;
5. 42 language image files verified present;
6. no screenshots generated.
After GitHub Pages deploy, use Ctrl+F5 once.
