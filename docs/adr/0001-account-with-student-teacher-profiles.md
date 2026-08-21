# Account identity with Student and Teacher profiles

We decided to model authentication with a shared `Account` identity and role-specific profiles (`Student`, `Teacher`) instead of keeping a generic `User` as the canonical domain term. This aligns code with the product language for educational clarity while avoiding duplicated auth logic per role. We accepted this because role separation is central to class management and consent-gated student participation.
