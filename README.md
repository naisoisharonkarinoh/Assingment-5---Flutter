A) Flutter Environment Audit and First Widget
<img width="952" height="515" alt="image" src="https://github.com/user-attachments/assets/f73d67a0-52df-428d-875e-2c5fc8b1e68c" />
<img width="957" height="558" alt="image (1)" src="https://github.com/user-attachments/assets/481c66ba-63bd-471d-ab26-bfc6da4c6905" />

B) MySQL Database Design and Querying
<img width="959" height="563" alt="Product 3" src="https://github.com/user-attachments/assets/bf29690b-3176-43fa-8de5-5e6d7e6c4c74" />
<img width="959" height="566" alt="Product 2" src="https://github.com/user-attachments/assets/3d518f93-d678-401c-9854-b3770e51863e" />
<img width="959" height="566" alt="Product 1" src="https://github.com/user-attachments/assets/ce9eb315-e539-4921-9676-e7701f6770d8" />

Explanation of DECIMAL(10,2)
DECIMAL(10,2) is a fixed-point numeric data type that stores numbers with up to 10 total digits, including 2 digits after the decimal point. It is preferred for currency values because it preserves exact decimal values and avoids rounding issues that can happen with floating-point types.

Why DECIMAL is preferred over FLOAT for currency
FLOAT stores numbers approximately, which can introduce tiny rounding errors when working with money. DECIMAL stores values exactly, so prices such as 19.99 or 45.75 are represented precisely and remain reliable for calculations and reporting.

What NOT NULL does
The NOT NULL constraint ensures that a column must always contain a value. If a row is inserted without a value for a NOT NULL column, MySQL will reject the insert and raise an error.
