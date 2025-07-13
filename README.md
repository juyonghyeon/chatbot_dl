# 1. 개요
Transformer 관련 모델을 바탕으로 챗봇을 구현하자!

# 2. 기능설명 및 코드리뷰
## train.ipynb
- base_model을 바탕으로 데이터학습 및 모델의 가중치 저장
- 기존 방대한 양의 문장 데이터를 사용하기 편한 데이터로 처리
  (data -> data2 -> chat_data + chat_data2 -> get_chat_data -> dataset)

## generate.inpyb
- Transformer 알고리즘 처리를 바탕으로 chatbot에 텍스트를 입력하고 답변을 받을 수 있음.

## generate.py
실질적으로 파이썬 기능이 실행되는 코드
- Transformer 알고리즘의 절차대로 chatbot 기능을 구현
- chatbot이 출력한 메시지를 json파일로 변환
