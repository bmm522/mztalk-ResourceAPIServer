# MZTALK-ResourceAPIServer

## Description

- ๐ ํ๋ก์ ํธ ์๊ฐ
  - ๊ฐ ์๋น์ค๋ค์ ์ฒจ๋ถ ํ์ผ๊ณผ ๊ด๋ จ๋ ํ๋ก์ธ์ค๋ฅผ ํต์ผํ๊ธฐ ์ํด ๊ฐ๋ฐ๋ API ์๋ฒ
  - ์ฒจ๋ถํ์ผ๊ณผ ๊ด๋ จ๋ CRUD ๋ก์ง ๊ฐ๋ฐ
  - `swagger`๋ฅผ ํตํด API ๋ฌธ์ ์์ฑ
  - MZTALK ํ๋ก์ ํธ : https://github.com/bmm522/mztalk
 
- ๐๏ธ ๊ฐ๋ฐ ๊ธฐ๊ฐ : 2022.12.10 ~ 2022.12.23

- ๐ ๏ธ ์ฌ์ฉ ๊ธฐ์ 
  - Java
  - Spring Boot, Spring Cloud Eureka, Spring Data JPA
  - Swagger, AWS S3
  - MySQL

## Project Structure

### 1. Flow

---

- ๋ชจ๋  ์๋น์ค์ ์ฒจ๋ถํ์ผ, ์ด๋ฏธ์ง๋ฅผ ํ๋์ ์ ์ฅ์๋ฒ๋ฅผ ๋ ์ผ๋ก์จ ์์ํจ์จ์ ์ฌ๋ ธ์ต๋๋ค.

![image](https://user-images.githubusercontent.com/102157839/218325752-8a7aa543-14cb-49de-aad6-fe81f95d29af.png)

- ์ ์ฅ Flow ์๋๋ค.

![image](https://user-images.githubusercontent.com/102157839/218325867-4f4d1dd4-a20b-4aa8-9d24-dde34b75a46c.png)

- ์ฒจ๋ถํ์ผ ๊ด๋ จ ์ฒ๋ฆฌ Flow ์๋๋ค.

![image](https://user-images.githubusercontent.com/102157839/218325923-00a994e8-2844-4438-9d5c-74976bf50fef.png)

---

### 2. Swagger

---

- ํ์๋ค์ด ํ์คํธ์ ๋ณด๊ณ  ์ฌ์ฉํ  ์ ์๋๋ก swagger๋ฅผ ํตํด api๋ฌธ์๋ก ์์ฑํ์ต๋๋ค.

<img width="700" alt="์ค์จ๊ฑฐ3" src="https://user-images.githubusercontent.com/102157839/218326596-ae1632b2-5e09-4430-b4af-5f580ce86a38.jpg">


---

