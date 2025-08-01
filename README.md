<div align="center">
  <img width="629" height="168" alt="Captura de tela 2025-08-01 182910" src="https://github.com/user-attachments/assets/fc39e1fc-1d42-44ea-a0cb-d90077340419" />

  # Search

**HarvardX CS50W - CS50's Web Programming with Python and JavaScript**
</div>

## About

Proposed as [Project 0](https://cs50.harvard.edu/web/projects/0/search/) by CS50W. A front-end built with HTML and CSS for Google Search, Google Image Search and Google Advanced Search. Includes the "I'm Feeling Lucky" and all the Advanced Search filters. Each search redirects the user to Google's results, through the `action` attribute with specific `GET` parameters.

## Searches

1. **Standard Search:**

   * Parameter: `q`
   * `<input type="text" name="q">`

2. **I'm Feeling Lucky:**

   * Parameters: `q`, `btnI`
   * `<input type="submit" name="btnI" value="I'm Feeling Lucky">`

<img width="1909" height="860" alt="Captura de tela 2025-08-01 181653" src="https://github.com/user-attachments/assets/346d18c8-e2ea-46d6-b868-a7f69054aab2" />

3. **Image Search:**

   * Parameters: `q`, `tbm`
   * `<input type="hidden" name="tbm" value="isch">`

<img width="1910" height="861" alt="Captura de tela 2025-08-01 181752" src="https://github.com/user-attachments/assets/c02e768f-afce-4751-a4d4-382707a6b61d" />

4. **Advanced Search:**

   * all these words:

     * Parameters: `as_q`
     * `<input type="text" id="as_q" name="as_q">`

   * this exact word or phrase:

     * Parameters: `as_epq`
     * `<input type="text" id="as_epq" name="as_epq">`

   * any of these words:

     * Parameters: `as_oq`
     * `<input type="text" id="as_oq" name="as_oq">`

   * none of these words:

     * Parameters: `as_eq`
     * `<input type="text" id="as_eq" name="as_eq">`

<img width="1910" height="860" alt="Captura de tela 2025-08-01 181829" src="https://github.com/user-attachments/assets/5b5fa271-a4b3-4253-a110-f8b516b6a391" />

## Video Demo

https://github.com/user-attachments/assets/f6f4f51f-4cf0-4dcf-a9a0-1dbf7b7a9cda

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact

Leonardo Santos - <leorsantos2003@gmail.com>
