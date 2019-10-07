Graja accepts both submissions with a result-spec of "merged-test-feedback" structure and with a result-spec of "separate-test-feedback" structure.

The file "response-separate.xml" is a Graja response for the "submission-separate.zip". Equivalently the file "response-merged.xml" is a Graja response for the "submission-merged.zip".

In "submission-merged.zip" we demonstrate, how the grading-hints-element of the task can be overridden by a modified grading-hints-element that is included with the submission. In the example in the file "submission.xml" the modified grading-hints changes the weights of the two functionality sub aspects to an equal value of 2.4 for both aspects.

Note: Currently there is a bug in Graja that does not handle nullification conditions correctly when generating a "separate-test-feedback" response, if the nullification condition operand of type test-reference is not referenced as a combine node child. Hence unfortunately, in the "response-separate.xml" the subtest-response element for id="dom.circle.grader.Tester#testMethod" is missing.
