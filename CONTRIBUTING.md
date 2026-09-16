# Contributing

## Local setup

Backend:

```
cd backend
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pytest
```

Frontend (once the Vite project is initialized):

```
cd frontend
npm install
npm run dev
```

## Making a change

1. Pick a card from the project board and move it to In Progress.
2. Create a branch from `main`: `git checkout -b feature/<short-description>`.
3. Commit in small steps with clear messages.
4. Push and open a pull request against `main`. Fill in the PR template and link the issue.
5. Wait for CI to pass and for one teammate to approve, then squash and merge.
6. Move the card to Done.

Do not push directly to `main`. Do not merge your own PR without a review.
