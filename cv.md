# Andrei Zhidelev

## Senior Test Automation Engineer

### Contact information

**E-Mail:** mcjanz@gmail.com

**Full CV:** [Linkedin](http://www.linkedin.com/in/azhidelev)

### Briefly about myself

I'm a seasoned Test Automation Engineer with more than 10 years of experience. I've worked with various types of systems from interactive voice systems with automatic speech recognition to solutions for e-commerce merchants. My experience is in Backend testing. That's why I am working on improving my skills related to Frontend development.

### Skills

- Python (FastAPI, pytest)
- Git
- CI/CD (Github, Gitlab, Jenkins)
- HTML, CSS
- JavaScript basics

### Code sample

[Kata](https://www.codewars.com/kata/5262119038c0985a5b00029f) - Define a function that takes an integer argument and returns a logical value true or false depending on if the integer is a prime.

Per Wikipedia, a prime number ( or a prime ) is a natural number greater than 1 that has no positive divisors other than 1 and itself.

```python
def is_prime(num):
  if num in [2, 3]:
    return True
  if num < 2:
    return False
  if num % 2 == 0 or num % 3 == 0:
    return False
  for n in range(5, int(num ** 0.5) + 1, 2):
     if num % n == 0:
        return False
  return True
```

### Work experience

#### Senior Test Automation Engineer at Behavox

2022-02 - Present

- Test automation for REST API (Python, pytest, Gitlab).
- Implementing test framework from scratch for Japanese functionality (100% test coverage for REST API, more than 500 test cases).

### Education

- Saint Petersburg University of Telecommunications (The audiovisual technologies)

### Courses

- 6.00.1x: Introduction to Computer Science and Programming Using Python ([certificate](https://s3.amazonaws.com/verify.edx.org/downloads/d2b493cb6a1c4eeba1508717883386e7/Certificate.pdf))

### Languages

- Russian (native)
- English (upper-intermediate)
- French (beginner)
- Serbian (beginner)
