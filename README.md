# redux_study
생활코딩님의 리덕스 강의 따라가기

# redux

Store 를 하나 두어서 store에서 state를 관리
전체적인 그림을 이해하자

![image](https://user-images.githubusercontent.com/53414542/129043995-d56054e6-0e16-445f-a7ef-ccc5e4a73f43.png)


# with-redux VS without-redux
리덕스를 사용하지 않으면 컴포넌트끼리 서로 의존이 심해서 하나를 수정하면 다른 컴포넌트도 수정해야하고, 수정하지 않으면 에러가 발생한다.
리덕스로 store에 중앙집중을 시켜두면 컴포넌트끼리 의존하지 않고 독립적이기 때문에 개별적으로 관리가 가능해진다. 따라서 복잡성이 사라지고, 코드가 간결해진다.