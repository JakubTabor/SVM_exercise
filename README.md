# SVM_exercise
# from "datasets" I import "load_digits" and save as "digits" """digits = load_digits()"""
# Then I set from my "DataFrame" my digits at "data" and "target" """digits.data, digits.target"""
# Next I create new column "target" """df['target'] = digits.target"""
# Then I import "train_test_split" and prepare my "train" and "test" set but without "target" column """df.drop('target', axis='columns')"""
# And import "SVC" model, set parameter "kernel" to "rbf" """rbf_model = SVC(kernel='rbf')"""
