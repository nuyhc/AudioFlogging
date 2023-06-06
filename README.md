## Part 0. 서론

## Part 1. DSP with Python
### 1-1. Intro
1. 신호의 수학적 표현
### 1-2. 정현파 (Sinusoids)
1. 정현파 신호
2. 정현파의 샘플링과 시각화
3. 복소 지수 함수와 페이저
4. 페이저 합
5. 시간 신호
### 1-3. 스펙트럼 (Spectrum)
1. 정현파들의 합에 대한 스펙트럼
2. 비트 음색
3. 주기적인 파형들
4. 푸리에 급수
5. 푸리에 급수 스펙트럼
6. 주기적인 신호의 푸리에 분석
7. 시간-주파수 스펙트럼
8. 주파수 변조: 처프 신호
### 1-4. 샘플링과 에일리어싱 (Sampling and Aliasing)
1. 샘플링
2. 샘플리의 스펙트럼 관찰과 복원
3. 이산-연속(DC) 변환
### 1-5. FIR 필터
1. 이산 시간 시스템
2. 이동 평균 필터
3. FIR 필터
4. 선형 시불변(LTI) 시스템
5. 콘볼루션과 LTI 시스템
6. 직렬 연결 LTI 시스템
7. FIR 시스템 정현파 응답
8. 중첩과 주파수 응답
9. 정상 상태와 과도 응답
10. 주파수 응답 시각화
11. 직렬 선형 불변 시스템 (cascaded LTI system)
12. 이동 평균 필터링
13. 샘플링된 연속시간 신호의 필터링
### 1-6. Z-변환
1. Z-변환의 정의
2. Z-변환과 선형 시스템
3. Z-변환의 특성
4. 연산자로써의 Z-변환
5. 콘볼루션 Z-변환
6. Z-영역과 w-영역의 관계
7. 유용한 필터들
### 1-7. 연속시간 신호와 LTI 시스템
1. 연속시간 신호
2. 단위 임펄스
3. 연속시간 시스템
4. 선형 시불변 시스템
5. 기본적인 LTI 시스템의 임펄스 응답
6. 임펄스의 콘볼루션
7. 콘볼루션 적분 계산
8. LTI 시스템의 성질
### 1-8. 주파수 응답
1. LTI 시스템에 대한 주파수 응답 함수
2. 실수 삼각함수 신호에 대한 응답
3. 이상적인 필터들
### 1-9. 연속시간 푸리에 변환
1. 푸리에 변환의 정의
2. 푸리에 변환과 스펙트럼
3. 푸리에 변환의 존재와 수렴
4. 푸리에 변환 짝
5. 콘볼루션 성질
6. 기본적인 LTI 시스템
7. 곱셈 특성
8. 푸리에 변환 특성과 변환표
### 1-10. 필터, 변조, 샘플링
1. 선형 시불변 시스템 (Linear Time-Invariant System)
2. 정현파 진폭 변조
3. 샘플링과 복원
### 1-11. 스펙트럼 계산
1. 유한 푸리에 합
2. 푸리에 변환 관계
3. 시간축에서의 윈도우
4. 삼각함수 합의 분석
5. 이산 푸레이 변환 (Discrete Fourier-Transform)
6. 유한 길이 신호들의 스펙트럼 분석
7. 주기적인 신호들의 스펙트럼 분석
8. 스펙트로그램
9. 고속 푸리에 변환 (FFT)

## Part 2. DASP(Digital Audio Signal Processing)
### 2-1. Discrete-Time Signal Processing
1. 디지털 신호 처리 개요 (Review of Discrete-Time Signal Processing)
2. z-변환 (The z-Transform)
3. 디지털 신호와 시스템의 주파수 해석 (Frequency Analysis of Discrete-Time Signals and Systems)
4. 연속시간 신호의 샘플링 (Sampling of Continuous-Time Signals)
5. 이산 푸리에 변환 (The Discrete Fourier Transform)
6. 효율적인 DFT 계산: FFT 알고리즘 (Efficient Computation of the DFT: FFT Algorithms)
7. 디지털 시스템의 구현 (Implementation of Discrete-Time Systems)
### 2-2. Waveform과 Physical Synthesis
1. 진폭과 주파수 변조 (Amplitude and Frequency Modulation)
2. 샘플링에서 고려해야 할 주파수 및 시간 영역 (Frequency and Time-Domain Considerations in Sampling)
3. 가산 합성과 필터 설계 (Additive Synthesis and Filter Design)
4. 변조된 합성 파형 (Modulated and Composite Waveforms)
5. 음향 시스템의 물리적 모델링 (Physical Modeling of Acoustic Systems)
### 2-3. Autocorrelation과 Pitch Detection
1. 자기상관함수 (Autocorrelation Function)
2. 자기상관을 이용한 음높이 감지 (Pitch Detection by Autocorrelation)
3. 제로 크로싱 비율 방법 (Zero-Crossing Rate Method)
4. 스펙트럼 분석 방법 (Spectral Analysis Method)
5. Harmonic Product Spectrum 방법 (Harmonic Product Spectrum Method)
### 2-4. Digital Effects Processing
1. 딜레이 효과 (Delay Effects)
2. 리버브 (Reverberation)
3. 변조 효과 (Modulation Effects)
4. 필터 효과 (Filter Effects)
5. 다이나믹스 처리 (Dynamics Processing)
6. 음높이 이펙트 및 하모나이제이션 (Pitch Shifting and Harmonization)
7. 시간 및 주파수 왜곡 효과 (Time and Frequency-Warping Effects)
### 2-5. Filter Banks과 Phase Vocoder
1. 필터 뱅크 (Filter Banks)
    - 필터 뱅크 설계 (Design of Filter Banks)
    - 분석 및 합성 필터 뱅크의 구현 (Implementation of Analysis and Synthesis Filter Banks)
2. 상대보강기(phase vocoder) (The Phase Vocoder)
    - 상대보강기 알고리즘 (Phase Vocoder Algorithm)
    - 시간 및 주파수 해상도 (Time and Frequency Resolution)
    - 상대보강기의 응용 (Applications of the Phase Vocoder)
### 2-6. 가청 모델과 오디오 코덱
1. 심리음향학 (Psychoacoustics)
    - 크리티컬 밴드 분석 (Critical Band Analysis)
    - 마스킹 (Masking)
2. MPEG-1 오디오 코더 (The MPEG-1 Audio Coder)
    - 서브밴드 코딩 (Subband Coding)
    - 심리음향 모델 (Psychoacoustic Model)
    - 비트 할당 및 전송 (Bit Allocation and Transmission)
3. MPEG-2 및 MPEG-4 오디오 코더 (MPEG-2 and MPEG-4 Audio Coders)
    - 고급 오디오 코딩(AAC) (Advanced Audio Coding (AAC))
    - 저비트 오디오 코딩 (Low Bit-Rate Audio Coding)
    - 확장 가능한 오디오 코딩 (Scalable Audio Coding)
    - 오디오 코딩 3(AC-3) (Audio Coding 3 (AC-3))
    - 고조파 및 순간적인 파형 코딩 (Harmonic and Transient Waveform Coding)
### 2-7. Sampling, Quantization, Dither
1. 샘플링의 기본 개념 (Basic Concepts of Sampling)
2. 연속시간 신호의 이산화 처리 (Discrete-Time Processing of Continuous-Time Signals)
3. 주파수 영역에서 신호의 모호성: 에일리어싱 (Aliasing: Signal Ambiguity in the Frequency Domain)
4. 샘플링 신호의 보간 (Interpolation of Sampled Signals)
5. 양자화 (Quantization)
6. 양자화 잡음 (Quantization Noise)
7. 오버샘플링 변환기 (Oversampling Converters)
8. 노이즈 쉐이핑 (Noise Shaping)
9. 디더링 (Dither)
### 2-8. Audio Signals의 Array Processing
1. Array Processing 소개 (Introduction to Array Processing)
2. 좁은 대역폭 빔포밍 (Narrowband Beamforming)
3. 넓은 대역폭 빔포밍 (Broadband Beamforming)
4. 공간 필터링 (Spatial Filtering)
5. 다채널 리버브 감소 (Multichannel Reverberation Reduction)
6. 도착 방향 추정 (Direction of Arrival Estimation)
7. 마이크로폰 어레이 보정 (Microphone Array Calibration)
8. 음성 및 오디오에 대한 Array Processing의 응용 (Applications of Array Processing to Speech and Audio)

## Part 3. Audio for ML/DL
- [DACON] 기계 고장 진단
- https://dacon.io/competitions/official/236036/codeshare/7106?page=1&dtype=recent
- [DACON] 음성 감정 인식
- https://dacon.io/competitions/official/236105/overview/description
- [DACON] 기계 고장 진단
- https://dacon.io/competitions/official/236036/overview/description
- [DACON] 영어 음성 국적 분류
- https://dacon.io/competitions/official/235738/overview/description
- [DACON] 음성 중첩 데이터 분류
- https://dacon.io/competitions/official/235616/overview/description

## Appendix