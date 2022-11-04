
# 0x09. React Redux reducer+selector

-   By:  Johann Kerbrat, Engineering Manager at Uber Works
-   Weight:  1
-   Ongoing second chance project - started  Oct 31, 2022 12:00 AM, must end by  Nov 8, 2022 12:00 AM
-   **Manual QA review must be done**  (request it when you are done with the project)

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/5b02610e1a538e005104.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20221104%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221104T005323Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d5227b07258ffa613b2329904b487f481e411d43ca4c1fa0cfbb6b055f033c20)

## Resources

**Read or watch:**

-   [Reducers](https://intranet.hbtn.io/rltoken/trY1MX9kqfGHJuBZNZ81gw "Reducers")
-   [Selectors](https://intranet.hbtn.io/rltoken/BTxJZN0xjsVICD9cQskGRQ "Selectors")
-   [Writing tests](https://intranet.hbtn.io/rltoken/R1ItiIAYYfpRKcRmkacr8w "Writing tests")
-   [Immutable Map documentation](https://intranet.hbtn.io/rltoken/Ap2lpTrq26l55SPkw1wFqw "Immutable Map documentation")
-   [Normalizr](https://intranet.hbtn.io/rltoken/0PRZtJeIoFMGZWRJtei3Rw "Normalizr")
-   [Normalizing State Shape](https://intranet.hbtn.io/rltoken/IV1ATmiv_IR158RAhN8Z3w "Normalizing State Shape")

## Learning Objectives

At the end of this project, you should be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/jdVIwKAFNuBfRST3piS_og "explain to anyone"),  **without the help of Google**:

-   The purpose of a reducer and the role it plays within your application
-   Why a reducer should stay as pure as possible
-   Why mutations should not happen within a reducer
-   The use of Immutable within the reducer
-   The use of Normalizr within the app
-   Selectors: what they are and when to use them

## Requirements

-   Allowed editors:  `vi`,  `vim`,  `emacs`,  `Visual Studio Code`
-   All your files should end with a new line
-   All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node  `12.x.x`  and  `npm 6.x.x`
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Push all of your files, including  `package.json`  and  `.babelrc`
-   All of your functions must be exported