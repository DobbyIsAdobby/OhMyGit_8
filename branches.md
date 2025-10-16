# Branches
## 1. Moving through the time
```
git checkout f7e4010da38f6f8b541178ab0f877ce63cdbccc6(가장 우측 commit이동)
- txt수정 후
git add .
git commit
```
## 2. Make parallel commits
```
git checkout b5582c4f85e4fdb97d0c4eef5e6e1f861a838b69(The child climbs somewhere)
- 두 txt 수정 후
git add .
git commit
```
## 3. Creating branches
```
git checkout f7f4d2fc977f322be517c2fb2ac036fc285832d6(Go to the birthday)
git branch birthday
git checkout e82088c14fec198022bcf8f7b376b84e1386c366(Go to the concert)
git branch concert
```
## 4. Branches grow with you!
```
git checkout 490400fe2d5ceb4351e9e8b3f78848f98241711e(Go to the birthday)
git add .
git commit -m birthday
git switch concert
git add .
git commit -m concert
```
## 5. Deleting branches
```
git branch -D friends
git branch -D ice-cream
git branch -D music
```
## 6. Moveing branches around
```
git switch baguette
git reset --hard 98bdba0ce988199409e7ab0a8c649470df62c646 (원래 coffee)
git switch coffee
git reset --hard d105ab9826a98d43be545d042b8aca7633f2477f (원래 baguette)
git switch donut
- You ate a donut. 수정
git add .
git commit
- 메시지에 You eat a donut 추가하여 save
