# Summary

* [README](README.md)
* [Introduction](Introduction/README.md)
* [Notation](Notation/README.md)
* [소스 코드 표현](Source code representation/README.md)
   * [Characters](Source code representation/characters.md)
   * [Letters and digits](Source code representation/letters_and_digits.md)
* [Lexical elements](Lexical elements/README.md)
   * [주석](Lexical elements/comments.md)
   * [언어요소](Lexical elements/tokens.md)
   * [세미콜론](Lexical elements/semicolons.md)
   * [식별자](Lexical elements/identifiers.md)
   * [예약어](Lexical elements/keywords.md)
   * [연산자와 구두점](Lexical elements/operators_and_punctuation.md)
   * [정수 리터럴](Lexical elements/integer_literals.md)
   * [부동 소수점 리터럴](Lexical elements/floating-point_literals.md)
   * [허수 리터럴](Lexical elements/imaginary_literals.md)
   * [룬 리터럴](Lexical elements/rune_literals.md)
   * [문자열 리터럴](Lexical elements/string_literals.md)
* [상수](Constants/README.md)
* [변수](Variables/README.md)
* [타입](Types/README.md)
   * [메서드 집합](Types/method_sets.md)
   * [불리언 타입](Types/boolean_types.md)
   * [숫자 타입](Types/numeric_types.md)
   * [string 타입](Types/string_types.md)
   * [배열 타입](Types/array_types.md)
   * [slice 타입](Types/slice_types.md)
   * [Struct 타입](Types/struct_types.md)
   * [pointer 타입](Types/pointer_types.md)
   * [Function 타입](Types/function_types.md)
   * [Interface 타입](Types/interface_types.md)
   * [Map 타입](Types/map_types.md)
   * [채널 타입](Types/channel_types.md)
* [타입과 값의 특성들](Properties of types and values/README.md)
   * [타입 아이덴티티](Properties of types and values/type_identity.md)
   * [할당 가능한 값의 조건들](Properties of types and values/assignability.md)
* [블록](Blocks/README.md)
* [Declarations and scope](Declarations and scope/README.md)
   * [라벨 범위](Declarations and scope/label_scopes.md)
   * [Blank identifier](Declarations and scope/blank_identifier.md)
   * [Predeclared identifiers](Declarations and scope/predeclared_identifiers.md)
   * [Exported identifiers](Declarations and scope/exported_identifiers.md)
   * [Uniqueness of identifiers](Declarations and scope/uniqueness_of_identifiers.md)
   * [Constant declarations](Declarations and scope/constant_declarations.md)
   * [Iota](Declarations and scope/iota.md)
   * [Type declarations](Declarations and scope/type_declarations.md)
   * [Variable declarations](Declarations and scope/variable_declarations.md)
   * [Short variable declarations](Declarations and scope/short_variable_declarations.md)
   * [Function declarations](Declarations and scope/function_declarations.md)
   * [Method declarations](Declarations and scope/method_declarations.md)
* [Expressions](Expressions/README.md)
   * [Operands](Expressions/operands.md)
   * [Qualified identifiers](Expressions/qualified_identifiers.md)
   * [Composite literals](Expressions/composite_literals.md)
   * [Function literals](Expressions/function_literals.md)
   * [Primary expressions](Expressions/primary_expressions.md)
   * [Selectors](Expressions/selectors.md)
   * [Method expressions](Expressions/method_expressions.md)
   * [Method values](Expressions/method_values.md)
   * [Index expressions](Expressions/index_expressions.md)
   * [Slice expressions](Expressions/slice_expressions.md)
   * [Type assertions](Expressions/type_assertions.md)
   * [Calls](Expressions/calls.md)
   * [여러 인자를 ...매개변수로 넘기기](Expressions/passing_arguments_to__parameters.md)
   * [연산자](Expressions/operators.md)
   * [산술 연산자](Expressions/arithmetic_operators.md)
   * [비교 연산자](Expressions/comparison_operators.md)
   * [논리적 연산자](Expressions/logical_operators.md)
   * [Address operators](Expressions/address_operators.md)
   * [Receive operator](Expressions/receive_operator.md)
   * [Conversions](Expressions/conversions.md)
   * [상수 식](Expressions/constant_expressions.md)
   * [Order of evaluation](Expressions/order_of_evaluation.md)
* [구문](Statements/README.md)
   * [종결문](Statements/terminating_statements.md)
   * [Empty statements](Statements/empty_statements.md)
   * [Labeled statements](Statements/labeled_statements.md)
   * [Expression statements](Statements/expression_statements.md)
   * [Send statements](Statements/send_statements.md)
   * [IncDec statements](Statements/incdec_statements.md)
   * [Assignments](Statements/assignments.md)
   * [If statements](Statements/if_statements.md)
   * [Switch statements](Statements/switch_statements.md)
   * [For statements](Statements/for_statements.md)
   * [Go statements](Statements/go_statements.md)
   * [Select statements](Statements/select_statements.md)
   * [Return statements](Statements/return_statements.md)
   * [Break statements](Statements/break_statements.md)
   * [Continue statements](Statements/continue_statements.md)
   * [Goto statements](Statements/goto_statements.md)
   * [Fallthrough statements](Statements/fallthrough_statements.md)
   * [Defer statements](Statements/defer_statements.md)
* [내장 함수](Built-in functions/README.md)
   * [Close](Built-in functions/close.md)
   * [길이와 용량](Built-in functions/length_and_capacity.md)
   * [할당](Built-in functions/allocation.md)
   * [Making slices, maps and channels](Built-in functions/making_slices,_maps_and_channels.md)
   * [Appending to and copying slices](Built-in functions/appending_to_and_copying_slices.md)
   * [Deletion of map elements](Built-in functions/deletion_of_map_elements.md)
   * [Manipulating complex numbers](Built-in functions/manipulating_complex_numbers.md)
   * [Handling panics](Built-in functions/handling_panics.md)
   * [Bootstrapping](Built-in functions/bootstrapping.md)
* [Packages](Packages/README.md)
   * [Source file organization](Packages/source_file_organization.md)
   * [Package clause](Packages/package_clause.md)
   * [Import declarations](Packages/import_declarations.md)
   * [An example package](Packages/an_example_package.md)
* [프로그램 초기화와 실행](Program initialization and execution/README.md)
   * [제로값](Program initialization and execution/the_zero_value.md)
   * [패키지 초기화](Program initialization and execution/package_initialization.md)
   * [프로그램 실행](Program initialization and execution/program_execution.md)
* [에러](Errors/README.md)
* [런타임 패닉](Run-time panics/README.md)
* [시스템 관련 고려사항들](System considerations/README.md)
   * [unsafe 패키지](System considerations/package_unsafe.md)
   * [크기와 얼라인먼트 보증](System considerations/size_and_alignment_guarantees.md)

