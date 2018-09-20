ZQCNN-v0.0��ZuoQing����mini-caffeд��forward�⣬�������

# ������־

**2018-09-20�ո���**

��������ʶ��ģ��tar-far���ȵĲ��Է��������԰��ղ���[How-to-evaluate-TAR-FAR-on-your-dataset](https://github.com/zuoqing1988/ZQCNN-v0.0/wiki/How-to-evaluate-TAR-FAR-on-your-dataset)���й�����Լ�����ģ�;��ȡ�

**2018-09-13�ո���**

(1)֧�ִ��ڴ����ģ��

(2)���ӱ�������ZQ_CNN_CompileConfig.h������ѡ���Ƿ�ʹ��_mm_fmadd_ps, _mm256_fmadd_ps (���Բ�һ���ٶȿ������׿��˻�������)��

**2018-09-12�ո��� ����[insightface](https://github.com/deepinsight/insightface)ѵ��112*96(��sphereface�ĳߴ�)���裺** [InsightFace�� how to train 112*96](https://github.com/zuoqing1988/ZQCNN-v0.0/wiki/InsightFace%EF%BC%9A-how-to-train-112*96)

**2018-08-15�ո���**

(1)�����Ȼ�����ı���⣬ģ�ʹ�[TextBoxes](https://github.com/MhLiao/TextBoxes)ת�����ġ��Ҹ��˾����ٶ�̫��������׼ȷ�Ȳ��ߡ�

ע�������Ŀ���õ�PriorBoxLayer��SSD���PriorBoxLayer�ǲ�ͬ�ģ�Ϊ�˵���ZQCNN��ʽ��Ȩ�����޸���deploy.prototxt����Ϊdeploy_tmp.prototxt��
��[�˴�](https://pan.baidu.com/s/1XOREgRzyimx_AMC9bg8MgQ)����ģ�͡�

(2)���ͼƬ���ƣ�ģ�ʹ�[open_nsfw](https://github.com/yahoo/open_nsfw)ת�����ģ�׼ȷ�ȸ߲�����Ҳû�����

��[�˴�](https://pan.baidu.com/s/1asjZFr3iTliQ4xlNbtKUtw)����ģ�͡�

**2018-08-10�ո���**

�ɹ�ת��mxnet�ϵ�[GenderAge-r50ģ��](https://pan.baidu.com/s/1f8RyNuQd7hl2ItlV-ibBNQ) �Լ�[Arcface-LResNet100E-IR](https://pan.baidu.com/s/1wuRTf2YIsKt76TxFufsRNA)����תMobileFaceNetģ�Ͳ���һ����
�鿴[mxnet2zqcnn](https://github.com/zuoqing1988/ZQCNN-v0.0/wiki/mxnet2zqcnn)

����Model Zoo ����ת�õ�ģ�ͣ����Զ�ת������Ӧ���Կ졣

��ZQCNN.sln����SampleGenderAge�鿴Ч������E5-1650V4��CPU�����߳�ʱ�䲨���ܴ󣬾�ֵԼ1900-2000ms�����߳�400��ms��

**2018-08-09�ո���**

���mxnet2zqcnn���ɹ���mxnet�ϵ�MobileFaceNetת��ZQCNN��ʽ�����ܱ�֤����ģ��Ҳ��ת�ɹ���ZQCNN����֧�ֺܶ�Layer�����鿴[mxnet2zqcnn](https://github.com/zuoqing1988/ZQCNN-v0.0/wiki/mxnet2zqcnn)

**2018-08-07�ո���**

BUG�޸���֮ǰConvolution, DepthwiseConvolution, InnerProduct, BatchNormScale/ScaleĬ��with_bias=true�� ���ڸĳ�Ĭ��with_bias=false��Ҳ����֮ǰ�Ĵ����޷����ز���bias���⼸��Layer��

ʾ������������һ��Layer����ǰ��Ĭ��Ϊ��bias_term������Ĭ��û��bias_term

Convolution name=conv1 bottom=data top=conv1 num_output=10 kernel_size=3 stride=1 

**2018-08-06�ո���**

��������ʶ����LFW���ݿ�ľ��Ȳ��ԡ���ZQlibFaceID.sln���Կ������Project��

����C++����ļ��㾫����matlab���в�࣬ͳ�Ƴ��ľ���Ҳ��һЩ��𣬵��������0.1%���ڡ�

**2018-08-03�ո���**

֧�ֶ��̣߳�ͨ��openmp���٣���**��ע�⣬Ŀǰ���̷߳����ȵ��߳���**

**2018-07-26�ո���**

֧��MobileNet-SSD��caffemodelת���õ�ģ�Ͳο�export_mobilenet_SSD_caffemodel_to_nchw_binary.m����Ҫ�����matcaffe���С�
�������������汾[caffe-ZQ](https://github.com/zuoqing1988/caffe-ZQ)

**2018-06-05�ո���**

����ʱ������������Դ�롣
����˵��Ҫ����openblas������ֱ���õ�mini-caffe������Ǹ��汾���Լ���������ĺ�����



# Model Zoo

**�������**

[MTCNN](https://pan.baidu.com/s/1f6_wQ2kXiTZFyH6PFIDc2Q) ��[MTCNN](https://github.com/kpzhang93/MTCNN_face_detection_alignment)ת�ĸ�ʽ

**����ʶ��**

|ģ��                                                                               |LFW����(ZQCNN)                                      | LFW����(OpenCV3.4.2)                              | LFW����(minicaffe)                               |��ʱ (ZQCNN)                       |��ע           
|------------                                                                       | -------------                                      |----------------------                             | ------------                                     |---------------------              | ------------- 
|[MobileFaceNet-res2-6-10-2-dim128](https://pan.baidu.com/s/1AQEad5Zp2cag4UA5KtpbYQ)|99.67%-99.55%(matlab crop), 99.72-99.60%(C++ crop)  |99.63%-99.65%(matlab crop), 99.68-99.70%(C++ crop) |99.62%-99.65%(matlab crop), 99.68-99.60%(C++ crop)|ʱ����dim256�ӽ� |����ṹ��dim256һ����ֻ�������ά����ͬ
|[MobileFaceNet-res2-6-10-2-dim256](https://pan.baidu.com/s/143j7eULc2AqpNcSugFdTxA)|99.60%-99.60%(matlab crop), 99.62-99.62%(C++ crop)  |99.73%-99.68%(matlab crop), 99.78-99.68%(C++ crop) |99.55%-99.63%(matlab crop), 99.60-99.62%(C++ crop)|���߳�Լ85ms�����߳�Լ30ms, 3.6GHz |����ṹ������������,��faces_emoreѵ���� 
|[MobileFaceNet-res2-6-10-2-dim512](https://pan.baidu.com/s/1_0O3kJ5dMmD-HdRwNR0Hpw)|99.52%-99.60%(matlab crop), 99.63-99.72%(C++ crop)  |99.70%-99.67%(matlab crop), 99.77-99.77%(C++ crop) |99.55%-99.62%(matlab crop), 99.62-99.68%(C++ crop)|ʱ����dim256�ӽ� |����ṹ��dim256һ����ֻ�������ά����ͬ����л[moli](https://github.com/moli232777144)ѵ����ģ��

|ģ��                                                                               |LFW����(ZQCNN)                                      | LFW����(OpenCV3.4.2)                              | LFW����(minicaffe)                               |��ʱ (ZQCNN)                       |��ע           
|------------                                                                       | -------------                                      |----------------------                             | ------------                                     |---------------------              | ------------- 
|[MobileFaceNet-res4-8-16-4-dim128](https://pan.baidu.com/s/1z6H5p4b3aVun2-1dZGDXkg)|99.72%-99.72%(matlab crop), 99.72-99.68%(C++ crop)  |99.82%-99.83%(matlab crop), 99.80-99.78%(C++ crop) |99.72%-99.72%(matlab crop), 99.72-99.68%(C++ crop)|ʱ����dim256�ӽ� |����ṹ��dim256һ����ֻ�������ά����ͬ
|[MobileFaceNet-res4-8-16-4-dim256](https://pan.baidu.com/s/1f_VtqNRxDNe972h8UrOsPw)|99.78%-99.78%(matlab crop), 99.75-99.75%(C++ crop)  |99.82%-99.82%(matlab crop), 99.80-99.82%(C++ crop) |99.78%-99.78%(matlab crop), 99.73-99.73%(C++ crop)|���߳�Լ135ms�����߳�Լ42ms, 3.6GHz |����ṹ������������,��faces_emoreѵ���� 
|[MobileFaceNet-res4-8-16-4-dim512](https://pan.baidu.com/s/14ukmtAWDhIJC6312WBhZhA)|99.80%-99.73%(matlab crop), 99.85-99.83%(C++ crop)  |99.83%-99.82%(matlab crop), 99.87-99.83%(C++ crop) |99.80%-99.73%(matlab crop), 99.85-99.82%(C++ crop)|ʱ����dim256�ӽ� |����ṹ��dim256һ����ֻ�������ά����ͬ����л[moli](https://github.com/moli232777144)ѵ����ģ��

|ģ��\���Լ�webface1000X50                                                          |thresh@ FAR=1e-7|TAR@ FAR=1e-7|thresh@ FAR=1e-6|TAR@ FAR=1e-6|thresh@ FAR=1e-5|TAR@ FAR=1e-5
|------------                                                                       | -------------  | ----------  |--------------- |-------      | ------------   |-----------                         
|[MobileFaceNet-res2-6-10-2-dim128](https://pan.baidu.com/s/1AQEad5Zp2cag4UA5KtpbYQ)|0.78785         |9.274%       |0.66616         |40.459%      |0.45855         |92.716%
|[MobileFaceNet-res2-6-10-2-dim256](https://pan.baidu.com/s/143j7eULc2AqpNcSugFdTxA)|0.77708         |7.839%       |0.63872         |40.934%      |0.43182         |92.605%
|[MobileFaceNet-res2-6-10-2-dim512](https://pan.baidu.com/s/1_0O3kJ5dMmD-HdRwNR0Hpw)|0.76699         |8.197%       |0.63452         |38.774%      |0.41572         |93.000%
|[MobileFaceNet-res4-8-16-4-dim128](https://pan.baidu.com/s/1z6H5p4b3aVun2-1dZGDXkg)|0.79268         |9.626%       |0.65770         |48.252%      |0.45431         |95.576%
|[MobileFaceNet-res4-8-16-4-dim256](https://pan.baidu.com/s/1f_VtqNRxDNe972h8UrOsPw)|0.76858         |9.220%       |0.62852         |46.195%      |0.40010         |96.929%
|[MobileFaceNet-res4-8-16-4-dim512](https://pan.baidu.com/s/14ukmtAWDhIJC6312WBhZhA)|0.76287         |9.296%       |0.62555         |44.775%      |0.39047         |97.347%

|ģ��\���Լ�webface5000X20                                                          |thresh@ FAR=1e-7|TAR@ FAR=1e-7|thresh@ FAR=1e-6|TAR@ FAR=1e-6|thresh@ FAR=1e-5|TAR@ FAR=1e-5
|------------                                                                       | -------------  | ----------  |--------------- |-------      | ------------   |-----------                         
|[MobileFaceNet-res2-6-10-2-dim128](https://pan.baidu.com/s/1AQEad5Zp2cag4UA5KtpbYQ)|0.70933         |29.558%      |0.51732         |85.160%      |0.45108         |94.313%
|[MobileFaceNet-res2-6-10-2-dim256](https://pan.baidu.com/s/143j7eULc2AqpNcSugFdTxA)|0.68897         |28.376%      |0.48820         |85.278%      |0.42386         |94.244%
|[MobileFaceNet-res2-6-10-2-dim512](https://pan.baidu.com/s/1_0O3kJ5dMmD-HdRwNR0Hpw)|0.68126         |27.708%      |0.47260         |85.840%      |0.40727         |94.632%
|[MobileFaceNet-res4-8-16-4-dim128](https://pan.baidu.com/s/1z6H5p4b3aVun2-1dZGDXkg)|0.71238         |32.153%      |0.51391         |89.525%      |0.44667         |96.583%
|[MobileFaceNet-res4-8-16-4-dim256](https://pan.baidu.com/s/1f_VtqNRxDNe972h8UrOsPw)|0.68490         |30.639%      |0.46092         |91.900%      |0.39198         |97.696%
|[MobileFaceNet-res4-8-16-4-dim512](https://pan.baidu.com/s/14ukmtAWDhIJC6312WBhZhA)|0.67303         |32.404%      |0.45216         |92.453%      |0.38344         |98.003%

|ģ��\���Լ�TAO ids:6606,ims:87210                                                  |thresh@ FAR=1e-7|TAR@ FAR=1e-7|thresh@ FAR=1e-6|TAR@ FAR=1e-6|thresh@ FAR=1e-5|TAR@ FAR=1e-5
|------------                                                                       | -------------  |-------------|--------------- |-------------| -------------- |-----------                         
|[MobileFaceNet-res2-6-10-2-dim128](https://pan.baidu.com/s/1AQEad5Zp2cag4UA5KtpbYQ)|0.92204         |01.282%      |0.88107         |06.837%      |0.78302         |41.740%
|[MobileFaceNet-res2-6-10-2-dim256](https://pan.baidu.com/s/143j7eULc2AqpNcSugFdTxA)|0.91361         |01.275%      |0.86750         |07.081%      |0.76099         |42.188%
|[MobileFaceNet-res2-6-10-2-dim512](https://pan.baidu.com/s/1_0O3kJ5dMmD-HdRwNR0Hpw)|0.90657         |01.448%      |0.86061         |07.299%      |0.75488         |41.956%
|[MobileFaceNet-res4-8-16-4-dim128](https://pan.baidu.com/s/1z6H5p4b3aVun2-1dZGDXkg)|0.92098         |01.347%      |0.88233         |06.795%      |0.78711         |41.856%
|[MobileFaceNet-res4-8-16-4-dim256](https://pan.baidu.com/s/1f_VtqNRxDNe972h8UrOsPw)|0.90862         |01.376%      |0.86397         |07.083%      |0.75975         |42.430%
|[MobileFaceNet-res4-8-16-4-dim512](https://pan.baidu.com/s/14ukmtAWDhIJC6312WBhZhA)|0.90710         |01.353%      |0.86190         |06.948%      |0.75518         |42.241%

��������ģ����鿴[Model-Zoo-for-Face-Recognition](https://github.com/zuoqing1988/ZQCNN-v0.0/wiki/Model-Zoo-for-Face-Recognition)

**����ʶ��**

[FacialEmotion](https://pan.baidu.com/s/1zJtRYv-kSGSCTgpvqc4Iug) ���������Fer2013ѵ��

**�Ա�����ʶ��**

[GenderAge-r50](https://pan.baidu.com/s/1FeuMLNG9jQ0CeD0ZANrY0g)��[insightface](https://github.com/deepinsight/insightface/wiki/Model-Zoo)��[gamodel-r50](https://pan.baidu.com/s/1f8RyNuQd7hl2ItlV-ibBNQ)ת�ĸ�ʽ��

**Ŀ����**

[MobileNetSSD](https://pan.baidu.com/s/1cyly_17cTOJBaCRiiQtWkQ) ��[MobileNet-SSD](https://github.com/chuanqi305/MobileNet-SSD)ת�ĸ�ʽ

[MobileNetSSD-Mouth](https://pan.baidu.com/s/1_l0Z1R34sOv2R73DB_zXyg) ����SampleDetectMouth

**���ּ��**

[TextBoxes](https://pan.baidu.com/s/1XOREgRzyimx_AMC9bg8MgQ) ��[TextBoxes](https://github.com/MhLiao/TextBoxes)ת�ĸ�ʽ

**ͼƬ����**

[NSFW](https://pan.baidu.com/s/1asjZFr3iTliQ4xlNbtKUtw) ��[open_nsfw](https://github.com/yahoo/open_nsfw)ת�ĸ�ʽ

# �������

(1)[�������������������洢������ʧ���٣�](https://zhuanlan.zhihu.com/p/35904005)

(2)[ǧ�������������������������ƶ����٣�](https://zhuanlan.zhihu.com/p/35955061)

(3)[����һ���mini-caffe�����Forward��](https://zhuanlan.zhihu.com/p/36410185)

(4)[��������ľ�������](https://zhuanlan.zhihu.com/p/36488847)

(5)[ZQCNN֧��Depthwise Convolution����mobilenet����һ��SphereFaceNet-10](https://zhuanlan.zhihu.com/p/36630082)

(6)[����ʱ������������һЩԴ��](https://zhuanlan.zhihu.com/p/37708639)

(7)[ZQCNN֧��SSD����mini-caffe����30%](https://zhuanlan.zhihu.com/p/40634934)

(8)[ZQCNN��SSD֧��ͬһ��ģ������ķֱ���](https://zhuanlan.zhihu.com/p/40676503)

(9)[ZQCNN��ʽ��99.78%���ȵ�����ʶ��ģ��](https://zhuanlan.zhihu.com/p/41197488)

(10)[ZQCNN��������ʶ����LFW���ݼ��ϵĲ��Դ���](https://zhuanlan.zhihu.com/p/41381883)

(11)[����mxnet�Ĵ��ȣ�����дmxnet2zqcnn](https://zhuanlan.zhihu.com/p/41667828)
