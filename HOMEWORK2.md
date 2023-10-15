# 리스트 생성
subjects = ["physics", "calculus", "poetry", "history"]
grades = [98, 97, 85, 88]

# 2차원 리스트 생성
gradebook = [["physics", 98], ["calculus", 97], ["poetry", 85], ["history", 88]]

# 출력
print(gradebook)

# 리스트에 computer science and visual arts grades 추가하기
gradebook.append(["computer science", 100])
gradebook.append(["visual arts", 93])

# GRADBOOK 수정
# 시각 예술 성적 5점 증가시키기
gradebook[5][1] = 98

# Switch poetry grade 를 PASS로 변경
poetry_index = subjects.index("poetry")
gradebook.pop(poetry_index)
gradebook.insert(poetry_index, ["poetry", "Pass"])

# 하나의 큰 성적표
last_semester_gradebook = [["politics", 80], ["latin", 96], ["dance", 97], ["architecture", 65]]
full_gradebook = last_semester_gradebook + gradebook

# 전체 성적표 출력
print(full_gradebook)

