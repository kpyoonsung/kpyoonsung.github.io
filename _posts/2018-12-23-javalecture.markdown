JAVA Lecture01

		// double a = 3.14;

		// 실수형 타입
		/*
		 * double float
		 */

		// + - * / %
		// 참 거짓 타입
		// boolean

		// 데이터 : 정수,자료형 타입
		/*
		 * short byte int long
		 */
		// int a = 10;
		// int b = 20;
		// int a,b; a=10;,b=20;
		// int c = a+b;

		// System.out.print(c);
		// System.out.println(a+b);
		// 변수 2개를 선언후 4칙연산한 결과를 출력하시오
		// int k=50;
		// int y=10;

		// System.out.println(k+y);
		// System.out.println(k-y);
		// System.out.println(k*y);
		// System.out.println(k/y);

		/*
		 * 빅맥에 가격은 5000원, 빅맥세트에 가격은 6500, 치즈스틱의 가격은 3000 태균이가 가서 빅맥 2세트와 치즈스틱 1개를 구매했을때
		 * 가격을 출력
		 */
		int a = 6500;
		int b = 3000;
		System.out.print(2 * a + b);

	}
JAVA Lecture02

package lecture_2018_12_23;

public class Lecture02 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		/*
		 * 문제3 애플 스토어 1 iphoneX $1000 2 iphone8 $800 3 iphone7 $700 4 airpod $10 5 ipad
		 * $2000 예원이가 애플스토어에서 iphoneX와 airpod 2개를 구매했다. 총 가격을 구하시오 세금은 총 가격의 10%가 추가된다.
		 * 각 변수명은 상품명과 동일하고 최종 가격의 변수는 totalPrice로한다.
		 *
		 */

		int iphoneX = 1000;
		int airpod = 10;
		double totalPrice = (iphoneX + airpod * 2) + (iphoneX + airpod * 2) * 0.1;
		System.out.print(totalPrice);

	}

}JAVA Lecture03

package lecture_2018_12_23;

public class Lecture03 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		/*
		 * int carName =10; // ==같다 // !=같지 않다. if(carName ==9) {
		 *
		 * System.out.print("내 자동차 이름은 10입니다."); }else {
		 * System.out.print("nnnnnnnnnnn"); }
		 */

		/*
		 * 기말고사를 봤는데 예원이의 수학점수는 100점입니다. 점수가 100점이면 "A+입니다"를 출력하시오, 100점 아래이면 "재수강입니다"를
		 * 출력하시오.
		 */
		int mathGrade = 95;
		if (mathGrade == 100) {
			System.out.print("A+입니다");
		} else {
			System.out.print("재수강입니다");
		}

	}

}

JAVA Lecture04

package lecture_2018_12_23;

public class Lecture04 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		/*
		 * 현우가 맥도날드에 갔다. 메뉴판 빅맥 5000 빅맥세트 6500 치즈스틱 3000 맥플러리 1500 현우는 빅맥 1개, 빅맥세트 2개,
		 * 치즈스틱 1개, 맥플러리 5개를 혼자먹으려고 다샀다. 현우가 계산한 금액이 20000원을 넘으면 "현우야 너무 많이 먹는다" 를 출력,
		 * 20000원 이하이면 "현우는 배가 안고프다"를 출력
		 *
		 */
		int bigMac = 5000;
		int bigMacSet = 6500;
		int cheese = 3000;
		int mac = 1500;

		int totalPrice = (bigMac + bigMacSet * 2 + cheese + mac * 5);
		if (totalPrice > 20000) {
			System.out.print("현우는 너무 많이 먹는다");
		} else {
			System.out.print("현우는 배가 안고프다");
		}

	}

}
