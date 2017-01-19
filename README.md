# Code Review

## Rules
  1. Everybody start with 3 points.

    _simulation_
    ```json
    {
        "Mr. A": 3,
        "Mr. B": 3,
        "Mr. C": 3
    }
    ```

  2. To ask for review, the submiter lost 1 point.

  3. To gain more point, you have to help review others, 1 point per pull request

    **example 1**: Mr. A ask Mr. B to review his pull request, Mr. A has to pay 1 point to Mr. B
    _simulation_
    ```json
    {
        "Mr. A": 2,
        "Mr. B": 4,
        "Mr. C": 3
    }
    ```

    **example 2**: Mr. A ask Mr. B and Mr. C to review his pull request, Mr. A has to pay 1 point to each of them.
    _simulation_
    ```json
    {
        "Mr. A": 1,
        "Mr. B": 4,
        "Mr. C": 4
    }
    ```

  4. If the pull request has more than 500 LOC, every 500 LOC, you will lost more 1 point (counting only 'added line')
    **example 3**: your pull request contains +499 LOC (and maybe, -200 LOC) = use 1 point.
    **example 4**: your pull request contains +501 LOC (and maybe, -1 LOC) = use 2 point.
    **example 5**: your pull request contains +1,001 LOC (and maybe, -159 LOC) = use 3 point.

  5. Submitter has a permission to choose whoever he/she wants to review the pull request.

  6. Reviewer also has a permission to deny Submitter's requests.

  7. If submitter's point is equal or lower than 1, submitter cannot ask for the review from others.

  8. Submitter can use 3 points to ask for "please review within 24 hrs"

  9. Submitter can use 4 points to ask for "please review immediately", this command, reviewer cannot deny.
