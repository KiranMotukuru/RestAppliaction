package com.example.demo.controller;

import org.springframework.web.bind.annotation.RequestParam;
import org.springframework.web.bind.annotation.GetMapping;

@org.springframework.web.bind.annotation.RestController
public class RestController {

    @GetMapping("/message")
    public String getMessage(@RequestParam(name = "msg", required = false, defaultValue = "Hello") String message) {
        return "Your message: " + message;
    }

}
