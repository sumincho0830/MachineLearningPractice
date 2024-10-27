# MachineLearningPractice
<b> bold<b>

<code>x = img_to_array(img)
x = np.expand_dims(x, axis=0)
x = preprocess_input(x)
all_img[num, :, :, :] = x

all_label[num] = 0  # no_glasses
num += 1
<code>
